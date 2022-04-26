<template>
  <div id="contact">
    <div>
      <b-container fluid class="bv-example-row">
        <b-row class="text-left">
          <b-col cols="4" class="contactTitle">
            <div class="mt-5">
              <h2>Get in Touch.</h2>
              <hr color="#fff" />
            </div>
          </b-col>
          <b-col cols="8" class="p-2">
            <div>
              <div class="underConstruction">
                <img src="@/assets/Construction.png" alt="construction" class="img-fluid" />
                <div class="underConstructionText">
                  <h3>Sorry, this page is still under development.</h3>
                  <p>For cooperation purposes and further information, please contact:<br>
                    <strong>Email: <a href="mailto:aldyfikhrimuhammad@gmail.com">aldyfikhrimuhammad@gmail.com</a></strong>
                  </p>
                </div>
              </div>
              <div style="margin-top: auto">
                <div class="text-left m-1"><h6>Also, You can contact me at:</h6></div>
                <div class="medsosContact">
                  <a href="https://www.linkedin.com/in/aldyfikhrimuhammad/" target="_blank"><b-icon class="m-2" icon="linkedin" font-scale="2" variant="dark"></b-icon></a>
                  <a href="https://github.com/aldyfikhrimuhammad" target="_blank"><b-icon class="m-2" icon="github" font-scale="2" variant="dark"></b-icon></a>
                  <a href="https://www.instagram.com/aldyfikh/" target="_blank"><b-icon class="m-2" icon="instagram" font-scale="2" variant="dark"></b-icon></a>
                </div>
              </div>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<style scoped>
h2 {
  font-weight: bolder;
  text-shadow: 1px 1px 3px #fff;
}
h3 {
  font-weight: bolder;
  text-shadow: 1px 1px 3px #000;
}
a {
  color: #fff;
}
a:hover {
  transition: 0.5s;
  transform: scale(1.2);
}
img {
  margin: 20px auto;
}
.contactTitle {
  background-color: #000;
  color: #fff;
}
.medsosContact {
  display: flex;
  justify-content: space-evenly;
  color: #000;
}
.underConstruction {
  position: relative;
  text-align: center;
}
.underConstructionText {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: #fff;
  text-shadow: 1px 1px 3px #000;
}
</style>

<script></script>
