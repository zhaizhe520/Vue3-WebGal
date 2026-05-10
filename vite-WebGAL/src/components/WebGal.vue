<template>
  <div class="webgal-container">
    <iframe 
      src="/game/index.html" 
      class="game-frame"
      frameborder="0"
    ></iframe>
  </div>
</template>

<style scoped>
/* 让游戏撑满整个屏幕 */
.webgal-container {
  width: 700px;
  height: 400px;
  margin: 0;
  padding: 0;
  overflow: hidden;
}

.game-frame {
  width: 100%;
  height: 100%;
}
</style>