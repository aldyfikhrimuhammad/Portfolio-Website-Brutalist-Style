<template>
  <div class="about">
    <b-container fluid class="bv-example-row" style="border: 2px solid black">
      <b-row>
        <b-col class="aboutContent contentLeft py-5 px-2 text-left">
          <div class="mb-2">
            <p>
              I am a Front End Website Developer completely oriented towards high level of detail and pleasant user experience. <br />
              Supported by a relevant educational background in the field of Information and Technology and with a career path set for the future as a web developer.
            </p>
          </div>
          <div class="buttonContainer p-3" style="">
            <b-button block variant="outline-dark" size="lg" class="homeButton">Download CV</b-button>
          </div>
        </b-col>
        <b-col class="aboutContent contentMid py-5 px-2 text-center">
          <div class="py-5">
            <h1 width="100%">ABOUT ME</h1>
            <hr />
          </div>
          <div style="border: 2px solid white; margin-top: auto">
            <div class="text-left p-2"><h6 style="border-bottom: 1px solid white">Social Media</h6></div>
            <div style="display: flex; justify-content: space-evenly">
              <b-icon class="m-2" icon="linkedin" font-scale="2"></b-icon>
              <b-icon class="m-2" icon="github" font-scale="2"></b-icon>
              <b-icon class="m-2" icon="instagram" font-scale="2"></b-icon>
            </div>
          </div>
        </b-col>
        <b-col class="aboutContent contentRight py-5 px-2 text-left">
          <div class="mb-2">
            <p>
              And with skills in using supporting technologies such as Javascript, VueJS, Bootstrap, Restful API using Axios. <br />
              Also critical thinking skills, teamwork and good problem solving, will be very useful and easy to implement in the developed program.
            </p>
          </div>
          <div class="buttonContainer p-3">
            <router-link to="/contact"><b-button block variant="outline-dark" size="lg" class="homeButton">HIRE ME</b-button></router-link>
          </div>
        </b-col>
      </b-row>

      <b-row>
        <b-col class="aboutContent">
          <div class="m-5 p-2">
            <b-carousel id="carousel-fade" style="" fade indicators img-width="480" img-height="144">
              <b-carousel-slide img-src="@/assets/Dashboard3D-Services.png"> </b-carousel-slide>
              <b-carousel-slide img-src="@/assets/SocialMedia3D-Services.png"> </b-carousel-slide>
              <b-carousel-slide img-src="@/assets/Copywriting3D-Services.png"> </b-carousel-slide>
            </b-carousel>
          </div>
        </b-col>
        <b-col class="aboutContent p-2 text-center">
          <h1>SERVICES</h1>
          <p>Some of the services I can provide.</p>
          <div>
            <div class="text-left mt-5">
              <h4>Web Development</h4>
              <h6 style="border-bottom: 2px solid black">Implementation of the UI/UX that has been made in a neat line of code that is carried out with high regard for client trust and satisfaction.</h6>
              <h4>Social Media Design</h4>
              <h6 style="border-bottom: 2px solid black">Creating an attractive and comfortable design to be able to bring in more audiences who like the social media content.</h6>
              <h4>Social Media Copywriting</h4>
              <h6 style="border-bottom: 2px solid black">Arrange a series of words that are able to convey the main message clearly and far from boring words, so that more audiences are interested in the content.</h6>
            </div>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<style scoped>
h1 {
  font-weight: bolder;
}
p {
  font-size: 1.2em;
  font-weight: bold;
}
.aboutContent {
  border: 2px solid black;
}
.buttonContainer {
  margin-top: auto;
  border-left: 2px solid black;
  border-right: 2px solid black;
}
.buttonContainer:hover {
  transition: 1s;
  transform: scale(1.1);
}
.contentRight {
  display: flex;
  flex-direction: column;
}
.contentMid {
  background-color: #000;
  color: #fff;
  display: flex;
  flex-direction: column;
}
.contentMid hr {
  border-color: #fff;
  width: 75%;
  border: 2px solid;
}
.contentLeft {
  display: flex;
  flex-direction: column;
}
</style>
