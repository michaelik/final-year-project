<template>
  <main id="mainContent">
  <section class="record-section">
    <figure class="record-svgs">
      <img src="../assets/img/sound.svg" class="record__svg-overlay" alt="record icon overlay">
      <img src="../assets/img/mic-start.svg" class="record__svg-record" alt="record button">
    </figure>
    <div class="record-button">
      <router-link to="/recording" href="/recording" class="btn btn--body">start Recording</router-link>
    </div>
  </section>
  </main>
</template>
