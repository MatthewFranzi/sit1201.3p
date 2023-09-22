<template>
    <body>
    <div class="contact">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <h1>Contact Me!</h1>
      <form>
        

      <label>Email</label>
      <input type="email" required v-model="email">

      <label>First Name</label>
      <input type="Fname" required v-model="Fname">

      <label>Last Name</label>
      <input type="Lname" required v-model="Lname">

      <label>Mobile</label>
      <input type="Mobile" required v-model="Mobile">

      <label>Occupation Of Contact</label>
      <select v-model="occup">
        <option value="Potential Employer">Potential Employer</option>
        <option value="Lecturer">Lecturer</option>
        <option value="Other">Other</option>
      </select>
      
      </form>

      <p> Email: {{ email }}</p>
      <p> First Name: {{ Fname }}</p>
      <p> Last Name: {{ Lname }}</p>
      <p> Mobile: {{ Mobile }}</p>
      <p> Occupation: {{ occup }}</p>


    </div>
    </body>
      


  </template>

  <script>
  export default {
    data() {
        return {
            email: '',
            Fname: '',
            Lname: '',
            Mobile: '',
            occup: '',
        }
    }
    
  }
</script>

<style>
* {
  box-sizing: border-box;
}
form {
    max-width: 420px;
    margin: 30px auto;
    background: white;
    text-align: left;
    padding: 40px;
    border-radius: 10px;

}

label {
    color: #aaa;
    display: inline-block;
    margin: 25px 0 15px
    font-size 0.6em;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: bold;
}
input {
    display: block;
    padding: 10px 6px;
    width: 100%;
    box-sizing: border-box;
    border: none;
    border-bottom: 1px solid #ddd;
    color: #555;
}

</style>

  