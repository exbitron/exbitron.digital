<template>
  <div class="">
    <div class="icon-main content-section">
      <div class="icon-scroll"></div>
    </div>
    <div class="content-section section--hidden" data-page="0">
      <div class="scroll-letters hidden">
        <span class="scroll-letters__letter" title="S">S</span>
        <span class="scroll-letters__letter" title="C">C</span>
        <span class="scroll-letters__letter" title="R">R</span>
        <span class="scroll-letters__letter" title="O">O</span>
        <span class="scroll-letters__letter" title="L">L</span>
        <span class="scroll-letters__letter" title="L">L</span>
      </div>
    </div>
  </div>
</template>

<style>
.hidden {
  display: none;
}
.icon-main {
  opacity: 0.1;
  position: absolute;
  top: 50% !important;
}
.icon-scroll,
.icon-scroll:before {
  position: absolute;
  left: 50%;
}
.icon-scroll {
  width: 40px;
  height: 70px;
  margin-left: -20px;
  top: 50%;
  margin-top: -35px;
  box-shadow: inset 0 0 0 1px #fff;
  border-radius: 25px;
}
.icon-scroll:before {
  content: "";
  width: 8px;
  height: 8px;
  background: #fff;
  margin-left: -4px;
  top: 8px;
  border-radius: 4px;
  animation-duration: 1.5s;
  animation-iteration-count: infinite;
  animation-name: scroll;
}
@-moz-keyframes scroll {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    transform: translateY(46px);
  }
}
@-webkit-keyframes scroll {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    transform: translateY(46px);
  }
}
@-o-keyframes scroll {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    transform: translateY(46px);
  }
}
@keyframes scroll {
  0% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    transform: translateY(46px);
  }
}
</style>