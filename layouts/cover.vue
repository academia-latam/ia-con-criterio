<template>
  <div class="slidev-layout cover h-full flex flex-col justify-between">
    <div class="flex items-center justify-between">
      <div class="wordmark text-[1.4rem] text-inkblue">Academ<span class="text-blue">IA</span>S</div>
      <div class="kicker">Webinar · en vivo</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <slot />
    </div>
    <div class="ac-rule pt-3 flex items-center justify-between">
      <div class="flex items-center gap-6">
        <div class="flex items-center gap-3">
          <div class="duo round photo w-12 h-12"><Img src="img/team-gaby.webp" alt="Gabriela" /></div>
          <div class="font-mono text-[0.72rem] leading-tight text-ink">Gabriela González<br /><span class="text-muted">directora AcademIA</span></div>
        </div>
        <div class="flex items-center gap-3">
          <div class="duo round photo w-12 h-12"><Img src="img/team-hesus.webp" alt="Hesus" /></div>
          <div class="font-mono text-[0.72rem] leading-tight text-ink">Hesus García<br /><span class="text-muted">mtro. en Pedagogía</span></div>
        </div>
      </div>
      <div class="kicker text-right">IA en educación<br />primero la pedagogía</div>
    </div>
  </div>
</template>
