<script>
  import BigButton from "../components/BigButton.svelte";
</script>

<style>
  :root {
    --main-color: #FFE99D;
  }

  div {
    display: flex;
    flex-flow: row;
    justify-content: center;
    margin: 30px 0 0 0;
    place-items: center;
  }

  h1,
  img {
    text-align: center;
    margin: 0;
  }

  h1 {
    font-size: 36px;
    font-weight: 200;
    margin: 20px 0 0;
  }

  img {
    display: block;
    height: 320px;
    margin: 0 auto;
    width: auto;
  }

  @media (min-width: 480px) {
    h1 {
      font-size: xxx-large;
    }
  }
</style>

<svelte:head>
  <title>OpenDGLab 项目</title>
</svelte:head>

<section class="projects">
  <div class="project-sapper">
    <img alt="OpenDGLab Project" src="logo.svg" />
  </div>
  <h1>OpenDGLab</h1>
  <div class="col">
      <p>OpenDGLab 旨在为 DG-Lab 设备提供一个开放的接入方式。</p>
      <p>让您的 DG-Lab 设备可以连接其他系统，获得更多快乐。</p>
  </div>
  <div class="usewrap" style="align-items: baseline; justify-content: space-evenly;">
    <div class="col">
      <img class="smheight" alt="OpenDGLab Core" src="OpenDGLab.svg" />
      <p class="removemargin subtitle">OpenDGLab 核心</p>
      <p class="removemargin">协议运算核心</p>
      <p class="removemargin">真正掌控您的设备</p>
      <p class="removemargin">让一切变得可能</p>
    </div>
    <div class="col">
      <img class="smheight" alt="OpenDGLab Remote" src="OpenDGLab-Remote.svg" />
      <p class="removemargin subtitle">OpenDGLab 远程协议</p>
      <p class="removemargin">原版 APP 远程协议</p>
      <p class="removemargin">通过协议兼容</p>
      <p class="removemargin">实现原版远程通讯协议</p>
      <p class="removemargin">与使用原始 APP 的玩家打通隔阂</p>
    </div>
    <div class="col">
      <img class="smheight" alt="OpenDGLab WaveGen" src="OpenDGLab-WaveGen.svg" />
      <p class="removemargin subtitle">OpenDGLab 波形生成</p>
      <p class="removemargin">使用网页调整波形</p>
      <p class="removemargin">导出您的自定义波形</p>
      <p class="removemargin">轻松使用您的波形</p>
    </div>
  </div>
  <hr style="margin-top: 24px ;border-top-style: none; border-color: transparent; background-color: #FFE99D;"/>
  <div class="col">
    <p class="removemargin subtitle">免责协议</p>
    <p class="removemargin">OpenDGLab 不对您使用 DG-Lab 设备发生的问题负责</p>
    <p class="removemargin">请遵循 DG-Lab 官方推荐安全使用设备</p>
  </div>
  <hr style="margin-top: 24px ;border-top-style: none; border-color: transparent; background-color: #FFE99D;"/>
  <div class="col">
    <p class="removemargin subtitle">非盈利项目</p>
    <p class="removemargin">本项目开发者不使用此项目盈利</p>
    <p class="removemargin">只为能让 DG-Lab 有更多可能</p>
    <p class="removemargin">协议库遵循 AGPL 协议开源</p>
  </div>
  <div class="col">
      <BigButton url="https://github.com/OpenDGLab">访问 GitHub 项目页</BigButton>
  </div>
</section>
