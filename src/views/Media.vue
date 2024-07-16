<template>
  <div>
    <h1>Media</h1>

    <div class="hover">
      <p class="hover__hover">Hover hover</p>
      <p class="hover__none">Hover none</p>
    </div>

    <div class="pointer">
      <p class="pointer__coarse">Pointer coarse</p>
      <p class="pointer__fine">Pointer fine</p>
      <p class="pointer__none">Pointer none</p>
    </div>

    <div class="orientation">
      <p class="orientation__landscape">Orientation landscape</p>
      <p class="orientation__portrait">Orientation portrait</p>
    </div>

    <div class="scheme">
      <p class="scheme__dark">Scheme dark</p>
      <p class="scheme__light">Scheme light</p>
    </div>
  </div>
</template>

<style>
@media (hover: hover) {
  .hover__hover {
    color: red;
  }
}

@media (hover: none) {
  .hover__none {
    color: red;
  }
}

@media (pointer: coarse) {
  .pointer__coarse {
    color: red;
  }
}

@media (pointer: fine) {
  .pointer__coarse {
    color: red;
  }
}

@media (pointer: none) {
  .pointer__none {
    color: red;
  }
}

@media (orientation: landscape) {
  .orientation__landscape {
    color: red;
  }
}

@media (orientation: portrait) {
  .orientation__portrait {
    color: red;
  }
}

@media (prefers-color-scheme: dark) {
  .scheme__dark {
    color: red;
  }
}

@media (prefers-color-scheme: light) {
  .scheme__light {
    color: red;
  }
}
</style>
