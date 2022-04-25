<template>
  <div id="contact">
    <div>
      <b-container fluid class="bv-example-row">
        <b-row>
          <b-col cols="4" style="border: 2px solid black; background-color: #000; color: #fff; text-align: left">
            <div>
              <h1>Lorem Ipsum</h1>
              <hr color="#fff" />
            </div>
            <div style="margin-top: auto">
              <div class="text-left m-1"><h6>Find me at</h6></div>
              <div style="display: flex; justify-content: space-evenly">
                <b-icon class="m-2" icon="linkedin" font-scale="2"></b-icon>
                <b-icon class="m-2" icon="github" font-scale="2"></b-icon>
                <b-icon class="m-2" icon="instagram" font-scale="2"></b-icon>
              </div>
            </div>
          </b-col>
          <b-col cols="8" class="p-2" style="border: 2px solid black">
            <b-container fluid class="bv-example-row">
              <b-row style="border: 2px solid black">
                <b-col sm="5" md="6" style="border: 2px solid black">sm="5" md="6"</b-col>
                <b-col sm="5" offset-sm="2" md="6" offset-md="0" style="border: 2px solid black">sm="5" offset-sm="2" md="6" offset-md="0"</b-col>
              </b-row>

              <b-row>
                <b-col sm="6" md="5" lg="6" style="border: 2px solid black">sm="6" md="5" lg="6"</b-col>
                <b-col sm="6" md="5" offset-md="2" lg="6" offset-lg="0" style="border: 2px solid black">sm="6" md="5" offset-md="2" col-lg="6" offset-lg="0"</b-col>
              </b-row>
            </b-container>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>
