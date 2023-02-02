<template>
    <div class="post-container">
      <router-link to="article">
        <div class="post-card">
          <img class="article-image" :src="image1" />
          <div class="description">
            {{ string1 }}
          </div>
        </div>
      </router-link>
      <router-link to="article2">
        <div class="post-card">
          <img class="article-image" :src="image2" />
          <div class="description">
            {{ string2 }}
          </div>
        </div>
      </router-link>
      <router-link to="article3">
        <div class="post-card">
          <img class="article-image" :src="image3" />
          <div class="description">
            {{ string3 }}
          </div>
        </div>
      </router-link>
    </div>
  </template>
  <script>
  export default {
    props: {
    image1: String,
    image2: String,
    image3: String,
    string1: String,
    string2: String,
    string3: String
  }
    }
  </script>


  <style scoped>
  .post-container {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
  }
  .post-card {
    width: 600px;
    height: 150px;
    margin: 10px;
    border: 1px solid #ccc;
    border-radius: 3px;
    padding: 10px;
    display: flex;
    align-items: center;
  }
  .article-image {
    height: 110%;
  }
  .description {
    width: 100%;
    display: flex;
    justify-content: center;
  }
  </style>
