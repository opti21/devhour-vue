<script setup lang="ts">
import YoutubeVideo from "./components/YoutubeVideo.vue";
import splitbee from "@splitbee/web";

splitbee.init();
</script>

<template>
  <div>
    <h1>DEVHOUR PODCAST</h1>
    <YoutubeVideo ytURL="https://www.youtube.com/embed/6Ab6ka_MKJ4" />
    <YoutubeVideo ytURL="https://www.youtube.com/embed/pvBHyip4peo" />
  </div>
</template>
