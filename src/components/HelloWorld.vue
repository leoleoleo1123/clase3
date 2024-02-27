<template>
  <div>
    Hello World
   <h3> {{ info }} </h3> 
  </div>
    
</template>

<script>
export default {
  data(){
    return{
      info: 'Leonardo Javier Molina Diaz 20988 5A'
    }
  }
}
</script>

<style>
.content-center {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100px;
    text-align: center; 
   
}
</style>