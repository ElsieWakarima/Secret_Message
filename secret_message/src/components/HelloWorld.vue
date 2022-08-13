<template>
  <form >
    <h1>Secret Message</h1>
    <input placeholder="Input Your Secret Message" class="message"><br>
    <Button>Submit</Button>
  </form>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;

}
input{
  border-radius:100rem;
  width:100%;
  height:100%;
}
Button {
  right:-100px;
  top:20px;
}


/* h3 {
  font-size: 1.2rem;
} */

/* .greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
} */
</style>
