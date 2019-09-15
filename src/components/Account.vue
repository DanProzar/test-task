<template>
  <div>
    <div class="d-flex block">
      <div class="text">
        <div class="name">
          <p>Superstar</p>
        </div>
        <div class="email">
          <p>Superstar@gmail.com</p>
        </div>
      </div>
      <div class="photo rounded-circle">
        <img src="../assets/user-superstar.jpg" alt="">
      </div>
      <div class="sign-out">
        <a href="#"><img src="../assets/sign-out.svg" alt=""></a>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  
}
</script>
<style lang="scss" scoped>
  .photo {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    img {
      width: 100%;
      border-radius: inherit;
    }
  }
  p {
    text-align: right;
  }
  .name {
    p {
      font-size: 0.88em;
      color: rgb(0, 0, 0);
      font-weight: 600;
    }
  }
  .email p {
    font-size: 12px;
    color: rgb(141, 140, 140);
  }
  .block {
    align-items: center;
    justify-content: space-between;
    width: 75%;
  }
</style>