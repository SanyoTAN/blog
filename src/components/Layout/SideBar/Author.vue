<template>
  <div>
    <!-- 作者信息 -->
    <div class="author-container">
<!--      &lt;!&ndash; 作者头像 &ndash;&gt;-->
<!--      <img class="author-avatar" :src="blog.blogInfo.siteConfig.authorAvatar" />-->
<!--      &lt;!&ndash; 作者名称 &ndash;&gt;-->
<!--      <p class="author-name">{{ blog.blogInfo.siteConfig.siteAuthor }}</p>-->
      <!-- 网站简介 -->
      <div class="site-desc">博客介绍</div>
    </div>
    <!-- 博客信息 -->
    <blog-info></blog-info>
    <!-- 社交 -->
    <social-list></social-list>
  </div>
</template>

<script setup lang="ts">
import { useBlogStore } from "@/store";
const blog = useBlogStore();

</script>

<style scoped></style>
