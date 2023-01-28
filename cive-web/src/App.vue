<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import Message from './components/Message.vue'

</script>
<script>
export default{ 
  
}
data() {
  return{
    counter:0;
    students: ["samia","Chima","Mbuya"],
    greet: true,
    message:" "
    }
  }

methods:{ 
  addValue() { 
    this.counter = this.counter+1;
  }
}
reduceValue(){
  this.counter = this.counter-1;
}else{ 
    alert("Counter can not be less than zero");
}, 

greet(){ 
  if(this.greet){ 
   
  }
}

showgreeting(){
  if(this.greet){ 
    this.message="Hello World";

  }else()
}
</script>
<template>

  <div>
  <button @click="addValue">add</button>
  
  <button @click="reduceValue">Reduce</button>


  <br/>
  {{ counter }}

  <ul>
    <li v-for="student in students">{{ student }}</li>
    </ul><ul>
    <button @click="reduceValue">Reduce</button>
    <button @click="ShowGreeting">Change Language</button>
    {{ message }}
  </ul>
  </template>

  <div>
    {{ name }}
  </div>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <Message></Message>
      <Message></Message>
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style> -->
