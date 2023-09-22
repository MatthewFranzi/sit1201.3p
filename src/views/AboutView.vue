<script setup>
import { ref } from "vue";

const show =ref(false);

</script>

<template>
  <body>
  <h1> Click here for a link to my linkedin! </h1>
  <h2 v-if="show"><a href="https://www.linkedin.com/in/matthew-franzi-6991641b2/">LinkedIn</a></h2>
  <button @click="show = !show">Toggle</button>
  <h1> A Short Bio: </h1>
  <p>Hi I'm Matt, I'm currently studying a bachelor of Cyber Security at Deakin. This trimester i've taken SIT120 as an elective to gain <br>
  insight into front end development and working with languages such as HTML, CSS and JavaScript as well Responsive Web Design. I have previously had little to no experience in <br>
  this field so it's been very informative to say the least! When I'm not fullfilling my commitments to Deakin University I'm working as bartender. <br>
  I work very odd hours and am called a nightowl by my partner, friends and family. I chose to study my degree as I enjoy helping people and feel as though <br>
  protecting online users from cyber criminals is the perfect way to continue doing this. Register your contact details on the relevant contact page to get in touch! <br>
 </p>
 <h1> Have A Great Day! </h1>
</body>
</template>
