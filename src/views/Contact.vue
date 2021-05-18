<template>
    <div class="inputWrapper">
        <h1>Contact Page</h1>

        <section class="inputSection">
        <input type="text" placeholder="First name..">
        <input type="text" placeholder="Last name..">
        <input type="email" placeholder="Type your e-mail..">
        <button class="submitButton">Submit</button>
        </section>
    </div>
</template>
<style scoped>
   .inputWrapper {
       background-color: beige;
       border-radius: 2%;
       box-shadow: 0px 1px 20px 01px #000000;
       width: 40%;
       padding: 1em;
       margin: 0 auto;
       margin-top: 2em;
       margin-bottom: 2em;
   } 
  .inputSection {
      display: flex;
      flex-direction: column;
      width: 50%;   
  }
  .submitButton {
      width: 50%;
      padding: 0.5em;
      background-color: white; 
      border: 1px solid black; 
      border-radius: 10%;
  }
</style>
