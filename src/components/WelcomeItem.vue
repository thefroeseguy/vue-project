<template>
  <div class="item">
    <i>
      <slot name="icon"></slot>
    </i>
    <div class="details">
      <h3 class="text-white">
        <slot name="heading"></slot>
      </h3>
      <slot></slot>
    </div>
  </div>
</template>


