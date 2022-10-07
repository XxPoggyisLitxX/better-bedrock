---
layout: home

hero:

  name: Better on Bedrock
  text: Download the Add-On and play Today!
  tagline: 
  image:
    src: ./images/logo.png
    alt: VitePress
  actions:
    - theme: brand
      text: Download
      link: /docs/images/logo.png 


---


<script setup>
import Post from './components/Post.vue'
</script>

<post align="center" title="Check my other work!" link="https://mcpedl.com/player-corpse/">
<p align="center">
   <img src="./images/plater_corpse_update_new.png"
	alt="alternative text"
	pixelated="true"
	width=420
  style="border-radius: 10px; outline-style: solid; outline-color:black">
</p>
</post>

<template>
    <div class="post">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<!-- Auto width -->
<button class="btn"><i class="fa fa-download"></i> Download</button>

<!-- Full width -->
<button class="btn" style="width:100%"><i class="fa fa-download"></i> Download</button>
    </div>
</template>

<style scoped>
   /* Style buttons */
.btn {
  background-color: DodgerBlue;
  border: none;
  color: white;
  padding: 12px 30px;
  cursor: pointer;
  font-size: 20px;
}

/* Darker background on mouse-over */
.btn:hover {
  background-color: RoyalBlue;
}
</style>