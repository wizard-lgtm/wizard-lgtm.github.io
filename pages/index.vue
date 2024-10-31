<template>
  <nav>
    <a href="/blog">my posts, please check them please read them :3</a>
  </nav>
  <img
    src="https://media.discordapp.net/attachments/1254558307402780824/1301389990273486868/image.png?ex=67244d60&is=6722fbe0&hm=888f9c3a775892160adb38e5d5ebc16c514df3140353bf84b00758affe4aa62d&=&format=webp&quality=lossless&width=1210&height=679"
    alt="logo"
    width="800"
    height="300"
  />

  <h1>Welcome to Wizard's bunker</h1>
  <b>Software programmer / Youtuber / And that's it idk </b>
  <p>
    Hey there, i'm just another random ass programmer jobless. after high school
  </p>

  <br />
  <b>Amigaos would be the topic of the next video!</b>
  <br />
  <img
    src="https://media.discordapp.net/attachments/1241146981435572325/1301337707217289347/New_Project.png?ex=67241caf&is=6722cb2f&hm=5baa4deaef2ed22d7173b1e86e096ca499cae7aefd69f768714d2cb09effb254&=&format=webp&quality=lossless&width=1652&height=928"
    alt="videothumbnail"
    width="500"
    height="300"
  />
  <h3>Known technologies as well:</h3>
  <ul>
    <li>Ziglang</li>
    <li>RISC-V</li>
    <li>Javascript and web development (unfortunately)</li>
  </ul>
  <h3>Some cool projects that i'm working on</h3>
  <ul>
    <li>
      <a href="https://github.com/wizard-lgtm/tiny-http-zig"
        >tiny-http-zig a, tiny web framework</a
      >
    </li>
    <li>
      <a href="https://github.com/wizard-lgtm/myos">an a cute RISC-V kernel</a>
    </li>
    <li>
      <a href="https://github.com/wizard-lgtm/ihatemylife-"
        >mongodb web server with c</a
      >
    </li>
  </ul>
  <h3>My interestings</h3>
  <ul>
    <li>
      <b>Operating systems and development of them</b>
    </li>
    <li>
      <b>SerenityOS and Ladybird</b>
    </li>
    <li>
      <b>Building webservers</b>
    </li>
    <li>
      <b>Devops</b>
    </li>
  </ul>
  <h3>Social</h3>
  <ul>
    <li>
      <a href="https://www.youtube.com/@xfxpositions">My youtube channel</a>
    </li>
    <li>
      <p>Discord username: <i>ziggywizard</i></p>
    </li>
  </ul>
  <h3>Persons that i raccomend to watch:</h3>
  <ul>
    <li><a href="https://www.youtube.com/@devaslife">Takuya Matsuyama</a></li>
    <li><a href="https://www.youtube.com/@awesomekling">Andreas Kling</a></li>
    <li><a href="https://www.youtube.com/@CoreDumpped">Core dumped</a></li>
    <li><a href="https://www.youtube.com/@PosyMusic">Posy</a></li>
    <li><a href="https://www.youtube.com/@templeos_archive">Terry davis</a></li>
  </ul>
  <div id="scroll-container">
    <h3>Whole list of technologies I know for nerds</h3>
    <ul id="">
      <li>Vue3</li>
      <li>Nuxt</li>
      <li>React</li>
      <li>HTTP</li>
      <li>AWS services</li>
      <li>Azure services</li>
      <li>C</li>
      <li>Linux (I can install arch from scratch btw)</li>
      <li>Hyprland</li>
      <li>How CPU works?</li>
      <li>Heap</li>
      <li>Stack</li>
      <li>Rust</li>
      <li>AmigaOS</li>
      <li>How compiler works</li>
      <li>English</li>
      <li>Learning Deutsch</li>
      <li>ZIGLANG I LOVE IT SO MUCH</li>
      <li>RISCV</li>
      <li>VGA text buffer</li>
      <li>How to be kind</li>
      <li>How to talk with girls</li>
      <li>The life of John Smith and Jesus</li>
    </ul>
  </div>

  <footer>
    <center>
      <a href="https://github.com/wizard-lgtm/">source. </a>
      <p>Btw i love writing a lot, you may check what i write</p>
      <p>Or we can talk on discord, i love talking too!</p>
    </center>
  </footer>
</template>

<style>
body {
  background-color: #121212;
  color: #f6f7f7;
}
a {
  color: #8c8de3;
}
#scroll-container {
  border-radius: 5px;

  overflow: hidden;
}

#scroll-text {
  height: 100%;
  text-align: center;

  -moz-animation: my-animation 15s linear infinite;
  -webkit-animation: my-animation 15s linear infinite;
  animation: my-animation 15s linear infinite;
}

/* for Firefox */
@-moz-keyframes my-animation {
  from {
    -moz-transform: translateY(0%);
  }
  to {
    -moz-transform: translateY(100%);
  }
}

/* for Chrome */
@-webkit-keyframes my-animation {
  from {
    -webkit-transform: translateY(0%);
  }
  to {
    -webkit-transform: translateY(100%);
  }
}

@keyframes my-animation {
  from {
    -moz-transform: translateY(-1%);
    -webkit-transform: translateY(-1%);
    transform: translateY(-1%);
  }
  to {
    -moz-transform: translateY(100%);
    -webkit-transform: translateY(100%);
    transform: translateY(100%);
  }
}
</style>
