<template>
  <div class="slidev-layout ac-split h-full flex flex-col justify-center">
    <div class="ac-split-head"><slot /></div>
    <div class="grid grid-cols-2 mt-4">
      <div class="pr-8"><slot name="left" /></div>
      <div class="pl-8 border-l border-[#DADEE6]"><slot name="right" /></div>
    </div>
  </div>
</template>
