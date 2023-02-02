<template>
    <div class="post-container">
      <router-link to="article">
        <div class="post-card">
          <img class="article-image" :src="image1" />
          <div class="description">
            My first Article
          </div>
        </div>
      </router-link>
      <router-link to="article2">
        <div class="post-card">
          <img class="article-image" :src="image2" />
          <div class="description">
            My Second Article
          </div>
        </div>
      </router-link>
      <router-link to="article3">
        <div class="post-card">
          <img class="article-image" :src="image3" />
          <div class="description">
            My third Article
          </div>
        </div>
      </router-link>
    </div>
  </template>
  <script>
  export default {
      data () {
        return {
          image1: '',
          image2: '',
          image3: ''
        }
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
    height: 100%;
  }
  .description {
    width: 100%;
    display: flex;
    justify-content: center;
  }
  </style>
