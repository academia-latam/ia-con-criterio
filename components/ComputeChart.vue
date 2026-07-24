<script setup>
// In-brand recreation of the AI-compute growth curve (data: Epoch AI / Our World in Data, CC BY).
// SVG lives inside a Vue component so markdown-it (mdc) never mangles it.
const dots = [
  [70,300],[120,296],[150,292],[200,298],[240,285],[300,288],[340,270],[380,276],
  [430,255],[470,262],[520,232],[560,244],[600,205],[640,214],[680,150],[710,168],[740,96],
]
</script>
<template>
  <svg viewBox="0 0 780 340" class="w-full" role="img" aria-label="El cómputo para entrenar IA crece de forma exponencial">
    <!-- baseline -->
    <line x1="50" y1="312" x2="762" y2="312" stroke="rgba(255,255,255,0.25)" stroke-width="1.5" />
    <line x1="50" y1="20" x2="50" y2="312" stroke="rgba(255,255,255,0.25)" stroke-width="1.5" />
    <!-- exponential trend -->
    <path d="M60 306 C 300 300, 470 265, 600 200 S 720 70, 752 40"
          fill="none" stroke="#EDF400" stroke-width="3" stroke-linecap="round" />
    <!-- scatter dots -->
    <circle v-for="(d,i) in dots" :key="i" :cx="d[0]" :cy="d[1]" r="4" fill="rgba(255,255,255,0.85)" />
    <!-- endpoint highlight -->
    <circle cx="752" cy="40" r="7" fill="#EDF400" stroke="#0B1C45" stroke-width="2" />
  </svg>
</template>
