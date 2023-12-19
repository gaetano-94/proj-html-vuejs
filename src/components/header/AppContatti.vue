<script>
export default {
  name: 'Contatti',
};
</script>

<template>
  <div>
    <ul class="container d-flex">
      <li>
        <div>
          <a href="#" class="pe-2">
            <i class="fa-solid fa-phone" style="color: grey"></i>
          </a>
          <a href="#" class="pe-3">+1 (305) 1234-5678</a>
        </div>
      </li>
      <li>
        <div>
          <a href="#" class="pe-2">
            <i class="fa-solid fa-envelope" style="color: grey"></i>
          </a>
          <a href="#" class="pe-3">hello@example.com</a>
        </div>
      </li>
      <li>
        <div>
          <a href="#" class="pe-5">
            <i class="fa-brands fa-facebook-f" style="color: grey"></i>
          </a>
          <a href="#" class="pe-5"
            ><i class="fa-brands fa-twitter" style="color: grey"></i
          ></a>
          <a href="#">
            <i class="fa-brands fa-linkedin-in" style="color: grey"></i>
          </a>
        </div>
      </li>
    </ul>
  </div>
</template>

<style scoped lang="scss">
ul {
  list-style-type: none;

  li {
    padding: 0px 10px;

    a {
      text-decoration: none;
      color: gray;
    }
  }
}
</style>
