<template>
  <div id="app">
    <Header/>
    <router-view/>
    <Footer/>
  </div>
</template>
<script>
import Header from '@/components/header/header.vue'
import Footer from '@/components/footer/footer.vue'
export default {
  components: {
    Header,
    Footer
  }
}
</script>
<style lang="scss">
*{
    margin: 0;
    padding: 0;
}
ul li{
    list-style: none;
}
input{  
	background:none;  
	outline:none;  
	border:none;
}
button{
border: none;
background-color: transparent;
outline: none;    
}


</style>
