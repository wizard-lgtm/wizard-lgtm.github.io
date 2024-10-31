<template>
  <div>
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">
const title = ref("wizard wizard wizard");
const description = ref(
  "OH HALO YOU WANNA ENTER? KOM PLEASE ICH WILL SEHR GUT DENN"
);

// This will be reactive when you change title/description above
useHead({
  title,
  meta: [
    {
      name: "description",
      content: description,
    },
    {
      name: "og:description",
      content: description,
    },
    {
      name: "og:image",
      content:
        "https://cdn.discordapp.com/attachments/1254558307402780824/1301389990273486868/image.png?ex=67244d60&is=6722fbe0&hm=888f9c3a775892160adb38e5d5ebc16c514df3140353bf84b00758affe4aa62d&",
    },
    {
      name: "image",
      content:
        "https://cdn.discordapp.com/attachments/1254558307402780824/1301389990273486868/image.png?ex=67244d60&is=6722fbe0&hm=888f9c3a775892160adb38e5d5ebc16c514df3140353bf84b00758affe4aa62d&",
    },
  ],
});
</script>
