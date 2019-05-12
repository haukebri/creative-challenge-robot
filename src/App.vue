<template>
  <div id="app">
    <div class="navbar container">
      <div class="row">
        <div class="col-md-12">
          <img
            src="./assets/reply-corporate-logo.png"
            class="reply-logo"
            alt=""
          />
          <span class="presents">presents:</span>
        </div>
      </div>
    </div>

    <div class="header">
      <div class="header-img-container">
        <img alt="Vue logo" class="header-img" src="./assets/header.svg" />
      </div>

      <div class="container text-left">
        <div class="row">
          <div class="col-md-4">
            <h2 class="centered">
              How she works
            </h2>
            <iframe
              width="360"
              height="160"
              src="https://www.youtube.com/embed/UdKBPbV29ek"
              frameborder="0"
              allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </div>
          <div class="col-md-4">
            <h2 class="centered">
              Reply AI
            </h2>
            <p>
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
              nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam
              erat, sed diam voluptua. At vero eos et accusam
            </p>
            <div class="centered">
              <button>Find AI Jobs at Reply</button>
            </div>
          </div>
          <div class="col-md-4">
            <h2 class="centered">
              Where to beat him
            </h2>
            <p>
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
              nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam
              erat, sed diam voluptua. At vero eos et accusam
            </p>
            <button class="full">See Locations</button>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <h1>
            Meet Sasha, the table soccer AI
          </h1>
        </div>
        <div class="col-md-5">
          <p>
            <b
              >Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
              nonumy eirmod tempor invidunt ut labore.</b
            >
            et dolore magna aliquyam erat, sed diam voluptua. At vero eos et
            accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren,
            no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum
            dolor sit amet, consetetur sadipscing elitr.
          </p>
          <img src="./assets/robot-hello.png" alt="" />
        </div>
        <div class="col-md-7">
          <img src="./assets/tablesoccer-16-9.jpg" alt="" />
          <img src="./assets/tablesoccer-4-3.jpg" alt="" />
        </div>
      </div>
    </div>

    <div class="blue">
      <div class="container text-left">
        <div class="row">
          <div class="col-md-12">
            <h2>How she works</h2>
          </div>
        </div>
        <div class="row ">
          <div class="col-md-8">
            <h3>Controlling the players</h3>
            <p>
              <b
                >Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed
                diam nonumy eirmod tempor invidunt ut labore.</b
              >
              et dolore magna aliquyam erat, sed diam voluptua. At vero eos et
              accusam et justo duo dolores et ea rebum. Stet clita kasd
              gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr.At vero
              eos et accusam et justo duo dolores et ea rebum. Stet clita kasd
              gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr.At vero
              eos et accusam et justo duo dolores et ea rebum. Stet clita kasd
              gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr.
            </p>
          </div>
          <div class="col-md-4">
            <img src="./assets/howitworks.png" alt="" />
          </div>
        </div>
        <div class="row mt-md">
          <div class="col-md-4">
            <img src="./assets/howitworks.png" alt="" />
          </div>
          <div class="col-md-8">
            <h3>Tracking the ball</h3>
            <p>
              <b
                >Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed
                diam nonumy eirmod tempor invidunt ut labore.</b
              >
              et dolore magna aliquyam erat, sed diam voluptua. At vero eos et
              accusam et justo duo dolores et ea rebum. Stet clita kasd
              gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr.At vero
              eos et accusam et justo duo dolores et ea rebum. Stet clita kasd
              gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr.At vero
              eos et accusam et justo duo dolores et ea rebum. Stet clita kasd
              gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr.
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row centered">
        <div class="col-md-12">
          <span>
            Imprint&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;Privacy&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;Reply
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "app"
};
</script>

<style lang="scss">
@import "css/flexboxgrid.min.css";
@import "css/button.scss";
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
* {
  transition: all 0.2s;
}
img {
  max-width: 100%;
}
h2,
h1 {
  color: #7bd4ba;
  font-size: 37px;
  line-height: 32px;
  font-family: "Indie Flower", cursive;
  font-weight: bold;
  text-shadow: 3px 3px 0 #000, -1px -1px 0 #000, 1px -1px 0 #000,
    -1px 1px 0 #000, 1px 1px 0 #000;
}
h1 {
  font-size: 44px;
}
h3 {
  color: #fff;
}
p {
  margin-top: 0;
}
.mt-md {
  margin-top: 100px;
}
.row {
  margin-bottom: 30px;
}
body,
html {
  padding: 0;
  margin: 0;
}
a {
  color: #192d27;
  text-decoration: none;
  font-weight: bold;
}
.navbar {
  height: 61px;
  background: #fff;
  margin-bottom: 0 !important;
  .presents {
    position: relative;
    left: -80px;
    top: -15px;
  }
  .reply-logo {
    max-height: 42px;
    padding-top: 15px;
    padding-left: 20px;
  }
}
.container {
  margin: 0 auto 40px auto;
}
.centered {
  text-align: center;
}
.text-left {
  text-align: left;
}
.header,
.blue {
  padding: 60px 0 90px 0;
  margin-bottom: 50px;
  text-align: center;
  background: linear-gradient(135deg, #2f6897 1%, #53a3d1 100%);

  p {
    color: #fff;
  }
  .header-img-container {
    margin-bottom: 40px;
  }
}
.header-img {
  max-width: 700px;
}
</style>
