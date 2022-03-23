<template>
  <!-- <h1 class="absolute top-1/4 left-1/2 transform -translate-x-1/2  font-Poppins text-5xl text-g-dark
	">Error 404  : Page Not Found !!</h1> -->
  <img
    src="../assets/images/error.jpg"
    alt=""
    class=" absolute w-2/5 left-1/2 top-1/5 transform -translate-x-1/2 -z-1"
  />
  <router-link
    :to="{ name: 'Home' }"
    class="absolute  left-1/2 transform -translate-x-1/2  font-Poppins text-5xl text-g-dark 
	"
    id="bth"
  >
    Back To Home</router-link
  >
</template>
<script>
export default {};
</script>
<style scoped>
h1 {
  text-shadow: 0px 5px 10px rgb(5, 255, 46);
}

#bth {
  top: 85%;
  background-color: rgb(18, 194, 76);
  color: rgb(255, 255, 255);
  padding: 15px 25px;
  z-index: 0;
}
#bth:hover {
  background-color: rgb(255, 255, 255);
  color: rgb(18, 194, 76);
  border: solid rgb(18, 194, 76);
  z-index: 50;
  background-position: 100% 100%;
  text-shadow: 0px 5px 10px rgb(5, 255, 46);
  box-shadow: 0px 5px 20px rgb(5, 255, 46);
}
</style>
