<template>
  <div>
 <PostList/>
 <About/>
</div>
</template>
<script>
import PostList from '../components/post/PostList.vue';
import About from '../components/home/About.vue';
export default {
components:{
  PostList,
  About
}
}
</script>
