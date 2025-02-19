## Hi there 👋


<div>
<a href="https://github.com/Trentin1">
<img loading="lazy" height="180em" src="https://github-readme-stats.vercel.app/api?username=Trentin1&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
<img loading="lazy" height="120em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Trentin1&layout=compact&langs_count=7&theme=dracula"/>
</div>


CSS : body {
  background: #000;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

html {
  height: 100%;
}

.loader {
  width: 70px;
  height: 70px;
  border-radius: 50%;
  position: relative;
}

.loader-outter,
.loader-inner {
  position: absolute;
  border: 4px solid #fff;
  border-radius: 50%;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}

.loader-outter {
  width: 100%;
  height: 100%;
  border-left-color: transparent;
  animation: rotate 1s cubic-bezier(0.15, 0.61, 0.58, 0.4) infinite;
}

.loader-inner {
  width: 35px;
  height: 35px;
  border-top-color: transparent;
  animation: rotate-reverse 1s cubic-bezier(0.15, 0.61, 0.58, 0.4) infinite;
}

@keyframes rotate {
  100% {
    transform: translate(-50%, -50%) rotate(360deg);
  }
}

@keyframes rotate-reverse {
  100% {
    transform: translate(-50%, -50%) rotate(-360deg);
  }
}
