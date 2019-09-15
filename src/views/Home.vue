<template>
  <div class="home">
    <Header />
    <section class="banner">
      <div class="container">
        <div class="title">
          <p>
            Test assignment for <br> Frontend Developer <br> position
          </p>
        </div>
        <div class="dop">
          <p>
            We kindly remind you that your test assignment should be submitted as a link to github/bitbucket repository. <br> Please be patient, we consider and respond to every application <br> that meets minimum requirements. We look forward to your submission. Good luck!
          </p>
        </div>
        <div class="btn-block">
          <button class="btn btn-sign-up">Sign Up</button>
        </div>
      </div>
    </section>
    <section class="about">
      <div class="container">
        <div class="title">
          <p>Let's get acquainted</p>
        </div>
        <div class="row main">
          <div class="col-md-4">
            <img src="../assets/man-mobile.svg" alt="">
          </div>
          <div class="col-md-8">
            <div class="title-about">
              <p>
                I am cool frontend developer
              </p>
            </div>
            <div class="text">
              <p>
                When real users have a slow experience on mobile, they're much less likely to find what they are looking for or purchase from you in the future. For many sites this equates to a huge missed opportunity, especially when more than half of visits are abandoned if a mobile page takes over 3 seconds to load.
              </p>
              <p>
                Last week, Google Search and Ads teams announced two new speed initiatives to help improve user-experience on the web.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Header from '../components/Header'
export default {
  name: 'home',
  components: {
    Header,
  },
  data() {
    return {
      
    }
  }
}
</script>
<style lang="scss" scoped>
  .banner {
    background: url('../assets/banner.jpg') no-repeat;
    background-position: -200px 0;
    background-size: cover;
    padding: 140px 0;
    margin-top: 60px;
    .title p {
      font-size: 3.125em;
      font-family: "Overpass", Arial;
      color: rgb(255, 255, 255);
      line-height: 1.3;
      text-align: left;
    }
    .dop {
      margin-top: 20px;
      max-width: 555px;
      p {
        font-size: 1.25em;
        color: rgb(255, 255, 255);
        line-height: 1.3;
        text-align: left;
      }
    }
    .btn-block {
      margin-top: 40px;
      width: 290px;
      button {
        font-size: 1.25em;
        color: rgb(254, 254, 254);
        font-weight: bold;
        text-align: center;
        border-radius: 4px;
        background-color: rgb(239, 108, 0);
        width: 100%;
        height: 40px;
        line-height: 1;
        border: none;
        transition: .3s;
        &:hover {
          background-color: #fc831f;
        }
      }
    }
  }
  .about {
    padding: 140px 0;
    .title p {
      font-size: 2.625em;
      font-family: "Overpass";
      color: rgb(0, 0, 0);
      font-weight: bold;
      line-height: 1.19;
      text-align: center;
    }
  }
</style>