<template>
  <div>

      <router-link to='login' class='btn btn-lg '>login</router-link>
      <router-link to='register' class='btn btn-lg'>register</router-link>

        <router-view></router-view>
  </div>
</template>

<script>
export default {

};
</script>
<style>
.router-link-active{
    /* line-height:80px; */
    border-radius: 4px;
    border:1px solid red;
    background-color:rgb(140, 248, 130)
}

</style>

