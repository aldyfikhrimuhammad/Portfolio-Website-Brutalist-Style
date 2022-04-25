<template>
  <div id="contact">
    <div>
      <b-container fluid class="bv-example-row">
        <b-row class="text-left">
          <b-col cols="4" class="contactTitle">
            <div>
              <h1>Get in Touch.</h1>
              <hr color="#fff" />
            </div>
            <div style="margin-top: auto">
              <div class="text-left m-1"><h6>Also, find me at</h6></div>
              <div class="medsosContact">
                <a href="https://www.linkedin.com/in/aldyfikhrimuhammad/" target="_blank"><b-icon class="m-2" icon="linkedin" font-scale="2"></b-icon></a>
                <a href="https://github.com/aldyfikhrimuhammad" target="_blank"><b-icon class="m-2" icon="github" font-scale="2"></b-icon></a>
                <a href="https://www.instagram.com/aldyfikh/" target="_blank"><b-icon class="m-2" icon="instagram" font-scale="2"></b-icon></a>
              </div>
            </div>
          </b-col>
          <b-col cols="8" class="p-2">
            <b-container fluid class="bv-example-row">
              <b-row>
                <b-col sm="5" md="6" class="formContact">sm="5" md="6"</b-col>
                <b-col sm="5" offset-sm="2" md="6" offset-md="0" class="formContact">sm="5" offset-sm="2" md="6" offset-md="0"</b-col>
              </b-row>

              <b-row>
                <b-col sm="6" md="5" lg="6" class="formContact">sm="6" md="5" lg="6"</b-col>
                <b-col sm="6" md="5" offset-md="2" lg="6" offset-lg="0" class="formContact">sm="6" md="5" offset-md="2" col-lg="6" offset-lg="0"</b-col>
              </b-row>
            </b-container>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<style scoped>
a {
  color: #fff;
}
a:hover {
  color: #ccc;
  transition: 0.5s;
  transform: scale(1.2);
}
.formContact {
  border: 2px solid black;
}
.contactTitle {
  background-color: #000;
  color: #fff;
}
.medsosContact {
  display: flex;
  justify-content: space-evenly;
}
</style>
