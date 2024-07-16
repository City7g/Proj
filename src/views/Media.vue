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
</style>
