<template>
  <h4>A podcast where three nerds (Alex, D.T. and Seth) hurtle through space, debating movies, books, games, and answering YOUR pop culture questions... all to maintain their own sanity!</h4>

  <p>
    <a href="https://www.youtube.com/channel/UCL9LooNWHVGILb5fB4JJvXQ/featured" target="_blank">
        <img src="../assets/YoutubeBadge.png" alt="">
    </a>
    <a href="https://open.spotify.com/show/0qeF4snFUsQYgjzmZeTGs8?si=Nmfh_1RPSWaX1GOagCn01Q&dl_branch=1" target="_blank">
        <img src="../assets/SpotifyBadge.png" alt="">
    </a>
    <a href="https://podcasts.apple.com/us/podcast/space-castle/id1499764926" target="_blank">
        <img src="../assets/AppleBadge.png" alt="">
    </a>
    <a href="https://podcasts.google.com/feed/aHR0cHM6Ly9sZXZlbHVweW91cmZhbmRvbS5jb20vZmVlZC9wb2RjYXN0L3NwYWNlLWNhc3RsZQ" target="_blank">
        <img src="../assets/GoogleBadge.png" alt="">
    </a>
  </p>
  <p class="schedule">
    New Episode Every Wednesday
    <div>(Hopefully)</div>
</p>
  <div class="bottom-stuff">
      <div class="logos">
          <a href="https://twitter.com/spacecastlepod" target="_blank">
              <img src="../assets/Twitter.png" alt="">
          </a>
          <a href="https://levelupyourfandom.com" target="_blank">
              <img src="../assets/LUYF.png" alt="">
          </a>
          <!-- <a href="https://www.youtube.com/channel/UCL9LooNWHVGILb5fB4JJvXQ/featured" target="_blank">
              <img src="../assets/YoutubeBadge.png" alt="">
          </a> -->
      </div>
      <div class="contact">
          <p>&copy; 2021 Space Castle</p>
          <a href="mailto:spcecastlepodcast@gmail.com">Email Us</a> | <a href="#">Privacy Statement</a>
      </div>
  </div>
</template>

<script setup>
import { defineProps, reactive } from 'vue'


const state = reactive({ count: 0 })
</script>

<style scoped>
a {

}

img {
    height: 3rem;
}

.bottom-stuff {
    margin-top: 3rem;
}

.bottom-stuff a {
    margin: 1rem;
    color: #fff;
}

.bottom-stuff p {
    margin: 0;
    padding: 0;
}

.bottom-stuff .contact {
    font-size: .75rem;
}

p.schedule {
    margin: 0;
}
</style>
