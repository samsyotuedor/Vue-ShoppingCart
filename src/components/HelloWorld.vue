<template>
  <div class="hello">
    <div class="sgnform"><br>
      <p id="sgnIn">Sign In</p>
      <b-form @submit.stop.prevent>
        <b-form-input type="text" id="email" placeholder="E-mail"></b-form-input><br>
        <b-form-input type="password" id="pass" placeholder="Password"></b-form-input><br>
        <b-button id="btn" variant="secondary">Log In</b-button><br>
      </b-form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  width: 30%;
  margin: auto;
  background-color: rgb(214, 201, 247);
  height: 20rem;
  border: 1px solid rgb(199, 199, 199);
  border-radius: 8px;
  box-shadow: 0px 8px 9px rgba(145, 145, 145, 0.9);
}
#name, #email, #pass{
  width: 75%;
  margin: auto;
  border-radius: 15px;
   box-shadow: 0px 8px 9px rgba(145, 145, 145, 0.9);
}
#btn{
  border-radius: 15px;
}
.sgnform p{
font-size: 23px;
font-weight: bolder;
}
</style>
