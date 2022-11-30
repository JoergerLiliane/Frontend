<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/SafetyPicturepng.png">
    <HelloWorld msg="Hello World"/>
  </div>
  <DynamicForm title = "Let's talk to the backend"> </DynamicForm>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
