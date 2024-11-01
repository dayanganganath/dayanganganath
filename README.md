<!-- Animated text example -->
<h1 align="center">Hi there! 👋 I'm Dayangananath</h1>

<!-- Blinking text effect -->
<p align="center">
  <span style="animation: blink 1s infinite;">I’m currently learning ...</span>
</p>

<!-- Typing animation for skills -->
<p align="center">
  <span id="skills">I’m interested in...</span>
</p>

<!-- CSS for animations -->
<style>
@keyframes blink {
  0% { opacity: 1; }
  50% { opacity: 0; }
  100% { opacity: 1; }
}

@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}

#skills {
  display: inline-block;
  white-space: nowrap;
  overflow: hidden;
  border-right: .15em solid orange;
  animation: typing 2s steps(30, end), blink-caret .75s step-end infinite;
}
</style>
