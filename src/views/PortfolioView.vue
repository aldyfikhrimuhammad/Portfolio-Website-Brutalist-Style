<template>
  <div id="portfolio">
    <div class="text-center" width="100%" style="border: 2px solid black">
      <h1>Portfolio</h1>
    </div>
    <div>
      <b-container fluid class="bv-example-row" style="border: 2px solid black">
        <b-row>
          <b-col cols="8" class="portfolioContent">
            <div class="m-2 p-2 text-left portfolioContent">
              <div class="titleBlog titleContent">
                <h3>Foccu Indonesia</h3>
                <h5>URL: <a href="https://foccu-indonesia.netlify.app//" target="_blank">Go to Website!</a></h5>
                <h5>Repository: <a href="https://github.com/aldyfikhrimuhammad/FOCCU-INDONESIA" target="_blank">Go to Github!</a></h5>
              </div>
              <div class="description mt-2">
                <p>
                  <strong>Foccu Indonesia</strong> is a digital agency engaged in graphic design and development website that was founded in 2021. Founded by young people from various regions in Indonesia Indonesia, which has a goal to help
                  develop the MSME sector in Indonesia to be more advanced and able to compete in this digitalization era.
                </p>
                <p>
                  In the creation and development of the Foccu Indonesia website I was in charge of make a mockup of the website's UI/UX design to implement it on the line the entire code from start to finish all pages, menus and features.
                </p>
                <p><strong>Technology Stacks:</strong> HTML, CSS, Javascript, Bootstrap, Responsive Design.</p>
              </div>
            </div>
          </b-col>
          <b-col cols="4" class="imgPorto">
            <div class="m-2">
              <img src="@/assets/Foccu Indonesia desktop.png" alt="Foccu-Indonesia Website" width="100%" height="100%" />
            </div>
          </b-col>
        </b-row>
        <b-row>
          <b-col cols="4" class="imgPorto">
            <div class="m-2">
              <img src="@/assets/HayuBaca desktop.png" alt="HayuBaca Website" width="100%" height="100%" />
            </div>
          </b-col>
          <b-col cols="8" class="portfolioContent">
            <div class="m-2 p-2 portfolioContent text-left">
              <div class="titleContent titleBlog">
                <h3>HayuBaca Website Blog</h3>

                <h5>URL: <a href="https://hayubaca.netlify.app/" target="_blank">Go to Website!</a></h5>
                <h5>Repository: <a href="https://github.com/rizkraf/hayu-baca" target="_blank">Go to Github!</a></h5>
              </div>
              <div class="description mt-2">
                <p>
                  <strong>HayuBaca!</strong> is a blog website that was developed by 3 young people from West Java, namely Aldy Fikhri Muhammad, Mohamad Arizal Hadisucipto, and Rizky Rafi Azhara who has the main goal of fulfilling the
                  mandatory graduation requirements in Chandradimuka Jabarcodingcamp program in the VueJS class organized by West Java government in collaboration with many parties.
                </p>
                <p>
                  In the creation and development of this website, I was involved in this team on duty to make a mockup of the UI design of the entire website page and perform styling / styling on the website using the BootstrapVue
                  framework.
                </p>
                <p><strong>Technology Stacks:</strong> VueJS, VueX, BootstrapVue, Axios, Responsive Design.</p>
              </div>
            </div>
          </b-col>
        </b-row>
        <b-row>
          <b-col cols="8" class="portfolioContent">
            <div class="m-2 p-2 text-left portfolioContent">
              <div class="titleBlog titleContent">
                <h3>Portfolio Website - Brutalist Design</h3>
                <h5>Repository: <a href="https://github.com/aldyfikhrimuhammad/Portfolio-Website-Brutalist-Style" target="_blank">Go to Github!</a></h5>
              </div>
              <div class="description mt-2">
                <p>
                  <strong>Aldy's Portfolio Website</strong> This is a website page created for the needs of Aldy Fikhri Muhammad's personal portfolio as a Front End Website Developer. Made by adapting the Brutalist design style and using
                  VueJS technology as the main framework to facilitate its development.
                </p>
                <p><strong>Technology Stacks:</strong> VueJS, BootstrapVue, Responsive Design.</p>
              </div>
            </div>
          </b-col>
          <b-col cols="4" class="imgPorto">
            <div class="m-2">
              <img src="@/assets/Portfolio desktop.jpg" alt="Portfolio Website" width="100%" height="100%" />
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<style scoped>
h1 {
  font-weight: bolder;
  text-shadow: 1px 1px 3px #000;
}
h3 {
  text-shadow: 1px 1px 3px #000;
}
a {
  color: #000;
  text-decoration: underline;
}
a:hover {
  transition: 0.5s;
  text-shadow: 1px 1px 3px #000;
}
.portfolioContent {
  border: 2px solid black;
}
.titleBlog {
  border-bottom: 2px solid black;
}
.imgPorto {
  border: 2px solid black;
  background-color: #000;
}
.titleContent h5 {
  white-space: normal;
}
</style>
