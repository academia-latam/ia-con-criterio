<template>
  <div class="slidev-layout cover h-full flex flex-col justify-between">
    <div class="flex items-center justify-between">
      <div class="wordmark text-[1.4rem] text-inkblue">Academ<span class="text-blue">IA</span>S</div>
      <div class="kicker">Webinar · en vivo</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <slot />
    </div>
    <div class="ac-rule pt-3 flex items-end justify-between text-muted">
      <div class="font-mono text-[0.72rem] leading-relaxed">
        <div class="text-ink">Gabriela González Domínguez <span class="text-muted">· directora AcademIA</span></div>
        <div class="text-ink">Hesus García Cobos <span class="text-muted">· diseñador curricular · mtro. en Pedagogía</span></div>
      </div>
      <div class="kicker text-right">IA en educación<br />primero la pedagogía</div>
    </div>
  </div>
</template>
