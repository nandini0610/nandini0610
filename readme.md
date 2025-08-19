<!-- Animated GitHub README Template -->

<h1 align="center">
  <span style="color:#00A9FF; animation: glow 2s ease-in-out infinite;">Hi, I'm [Your Name]</span> 👋
</h1>

<p align="center">
  <span id="typing-text" style="font-size:20px;"></span>
</p>

<style>
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}
@keyframes blink {
  50% { border-color: transparent }
}

.typewriter {
  display: inline-block;
  border-right: 2px solid;
  white-space: nowrap;
  overflow: hidden;
  animation: typing 4s steps(40) infinite, blink .75s step-end infinite;
}

@keyframes bounce {
  0%, 20%, 50%, 80%, 100% {transform: translateY(0);}
  40% {transform: translateY(-6px);}
  60% {transform: translateY(-3px);}
}

.icon-bounce {
  display: inline-block;
  animation: bounce 2s infinite;
}

@keyframes glow {
  0% { text-shadow: 0 0 5px #00a9ff; }
  50% { text-shadow: 0 0 20px #00a9ff; }
  100% { text-shadow: 0 0 5px #00a9ff; }
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function(){
  const typingText = document.getElementById("typing-text");
  typingText.classList.add("typewriter");
  typingText.textContent = "A passionate Developer and ML Enthusiast";
});
</script>

<hr/>

<h2>🛠️ Skills</h2>
<p>
  <span class="icon-bounce">⚡ HTML</span>&nbsp;&nbsp;
  <span class="icon-bounce">⚡ CSS</span>&nbsp;&nbsp;
  <span class="icon-bounce">⚡ JavaScript</span>&nbsp;&nbsp;
  <span class="icon-bounce">⚡ Python</span>
</p>

<h2>📈 GitHub Stats</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YourUsername&show_icons=true" />
</p>

<hr/>

<p align="center">
  <span>Made with ❤️ by [Your Name]</span>
</p>
