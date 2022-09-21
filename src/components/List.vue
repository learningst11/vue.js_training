<template>
  <div>
    <h5>{{블로그글[0].title}}</h5>
    <p>{{블로그글[0].date}}</p>
  </div>

  <div>
    <h5></h5>
    <p></p>
  </div>

  <div>
    <h5>블로그 글 제목</h5>
    <p>블로그 글 날짜</p>
    <p>블로그 글 날짜</p>
  </div>

</template>

<script>

export default {
    name:'list',
    props:{
      블로그글 : Array,
    }
}
</script>

<style>

</style>