<template>
  <div class="about">
      <img src="../assets/img/about.png" alt="">
    <h1>About this app..</h1>
    <p>dipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali. dipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali..</p>
     <p>dipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
      <p>dipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
           <p>dipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
      <p>dipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
           <p>dipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
      <p>dipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
    
  </div>
</template>

<script>
export default {
  name: 'Skills',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,700');


.about {
    background: white;
    float: left;
    height: 550px;
}
img{
    height: 200px;
    width: 200px;
    padding: 20px;
    float: left;
}
</style>