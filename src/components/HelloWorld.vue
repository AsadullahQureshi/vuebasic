<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  },
  name:{
    type: String,
    required: true

  },
  jobtitle:{
    type:String,
    required: true

  }

})
</script>

<template>
  <div class="greetings">    
    <h3>
      You’ve successfully created a project with
    </h3>
    <p>{{msg}}</p>
    <p>Name: {{name}}</p>
    <p>Job Title: {{jobtitle}}</p>
  </div>
</template>

<style scoped>

</style>
