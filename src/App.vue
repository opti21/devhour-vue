<script setup lang="ts">
import YoutubeVideo from "./components/YoutubeVideo.vue";
import splitbee from "@splitbee/web";

splitbee.init();
</script>

<template>
  <head>
    <title>Dev Hour Podcast - Home</title>
    <meta content="Dev Hour Podcast - Home" property="og:title" />

    <meta content="Dev Hour Podcast" property="og:site_name" />

    <meta
      content="https://img.youtube.com/vi/6Ab6ka_MKJ4/sddefault.jpg"
      property="og:image"
    />
    <meta name="twitter:card" content="summary_large_image" />
    <meta
      name="twitter:image"
      content="https://img.youtube.com/vi/6Ab6ka_MKJ4/sddefault.jpg"
    />
  </head>
  <div>
    <h1>DEVHOUR</h1>
    <img src="https://c.tenor.com/E3BS4gXTT6AAAAAC/deez-nuts.gif" />
    <h1>PODCAST</h1>
    <br />
    <YoutubeVideo ytURL="https://www.youtube.com/embed/6Ab6ka_MKJ4" />
    <YoutubeVideo ytURL="https://www.youtube.com/embed/pvBHyip4peo" />
  </div>
</template>
