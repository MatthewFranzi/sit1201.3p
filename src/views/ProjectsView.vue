<script setup>
import {ref} from 'vue'


const projects = ref([
    {id: 0, name: 'Task 1.1p', description: 'Created a HTML file, Added CSS to the HTML page, Got started with Git and Github.'},
    {id: 1, name: 'Task 1.2p', description: 'Learnt and implemented Responsive Web Design, JavaScript in HTML and relevant methods.'},
    {id: 2, name: 'Task 1.3p', description: 'Built a website using HTML, CSS and Vue 3.'},
])

</script>


<template>
    <body>
  

<h1> My Past Projects Within This Unit: </h1>
    <div v-for="project in projects">
    <table style="width:100%">
     <th><h1>{{ project.name }}</h1></th>
     
     <tr><td><h2>{{ project.description }}</h2></td></tr>
    </table>
    </div>
    </body>

</template>
 
<style>
table, th, td {
  border:10px solid black;
}
</style>
  
  
  