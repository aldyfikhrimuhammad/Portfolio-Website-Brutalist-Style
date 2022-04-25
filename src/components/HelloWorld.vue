<template>
  <b-container fluid class="bv-example-row homeContent">
    <b-row>
      <b-col style="border: 2px solid black">
        <div class="contentLeft p-4 m-5">
          <h1>Hi!<br />I'm Aldy Fikhri<br /></h1>
          <h3>And i'm Front End Web Developer</h3>
        </div>
        <div class="buttonContainer buttonContainer1 p-3 mb-4">
          <div class="buttonContainer buttonContainer2 p-3">
            <b-button variant="dark" size="lg" class="homeButton">Hire Me!</b-button>
          </div>
        </div>
      </b-col>
      <b-col style="border: 2px solid black">
        <div class="contentRight p-4 m-4">
          <img src="@/assets/homePictures.jpeg" alt="Profile-Picture" width="65%" height="65%" style="border-radius: 25px; box-shadow: 26px 26px 51px #9e9e9e, -26px -26px 51px #ffffff" />
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-size: 2.5em;
  font-weight: bold;
}
.homeContent {
  border-top: none;
  border-bottom: 2px solid black;
  border-left: 2px solid black;
  border-right: 2px solid black;
}
.contentLeft {
  text-align: left;
}
.buttonContainer {
  border: 2px solid black;
  box-sizing: border-box;
}
.buttonContainer1:hover {
  transition: 0.5s;
  border-top: none;
  border-bottom: none;
  transform: scale(0.9);
}
.buttonContainer2:hover {
  transition: 0.5s;
  border-left: none;
  border-right: none;
  transform: scale(1.1) !important;
}
.homeButton {
  font-weight: bold;
  border: 2px solid black;
  width: 98%;
}
.homeButton:hover {
  transition: 0.5s;
  background-color: #fff;
  color: #000;
  font-weight: bold;
  border: 2px solid #000;
}

</style>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>
