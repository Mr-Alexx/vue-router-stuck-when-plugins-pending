<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div>
      <router-link to="/">首页</router-link>
    </div>
    <div>
      <button class="button" @click="$router.go(-1)">
        返回home页（router.go(-1)形式）
      </button>
    </div>
    <!-- <button class="button" @click="$router.back()">返回home页</button> -->
  </div>
</template>

<style lang="css">
  .button {
    appearance: none;
    background-color: red;
    color: #fff;
    font-size: 16px;
    padding: 20px;
  }
</style>
