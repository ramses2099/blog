<template>
  <div>
    <p class="fs-1">home</p>
    <p class="fs-3">{{name}}</p>
    <p class="fs-3">{{age}}</p>    
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  setup(){
    console.log('setup hook')

    let name = 'clone'
    let age = 30
    
    //object
    return { name, age}
  }
  
}
</script>
