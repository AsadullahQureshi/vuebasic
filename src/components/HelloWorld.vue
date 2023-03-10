<script>
// import { defineComponent } from 'vue'

// defineProps({
//   msg: {
//     type: String,
//     required: true
//   },
//   name:{
//     type: String,
//     required: true

//   },
//   jobtitle:{
//     type:String,
//     required: true

//   },
//   salary:{
//     type:Number,

//   },

// });
export default {
   props: {
    msg: String,
    name: String,
    jobtitle: String,
    salary: Number,
    // likes: Number
  },

  data() {
    return { count: 0 }
  },

}
</script>

<template>
  <div class="greetings">
    <h3>You’ve successfully created a project with</h3>
    <p>{{ msg }}</p>
    <p>Name: {{ name }}</p>
    <p>Job Title: {{ jobtitle }}</p>
    <p>Salary: {{ salary }}</p>
    <button @click="salary++">Add Increment</button>
  </div>
</template>

<style scoped>
</style>
