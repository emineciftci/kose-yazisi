<template>
  <div>
 <PostList :posts="fetchedPosts"/>
</div>
</template>
<script>
import PostList from '../../components/post/PostList.vue';
export default {
components:{
  PostList,
},
asyncData(context,callback){
  setTimeout(()=>{callback(null,{
    fetchedPosts:[
    {
        id: "1",
        title:"Başlık",
        subTitle:"Alt Başlık",
        text:"Yazı Alanımız",
        author:"Yazar",
      },
      {
        id: "2",
        title:"Başlık 2",
        subTitle:"Alt Başlık 2",
        text:"Yazı Alanımız 2",
        author:"Yazar 2",
      }
    ]
  })},2000)

}
}
</script>
