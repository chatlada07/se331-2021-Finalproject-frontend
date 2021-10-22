<template>
  <title>W3.CSS Template</title>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css" />
  <link
    rel="stylesheet"
    href="https://fonts.googleapis.com/css?family=Inconsolata"
  />

  <body>
    <header class="w3-display-container w3-grayscale-min" id="home"></header>
    <!-- Add a background color and large text to the whole page -->
    <div class="w3-sand w3-grayscale w3-large">
      <div class="img">
        <img
          src="https://i2.fpic.cc/file/img-b1/2021/08/14/Covid.jpg"
          alt="Covid.jpg"
          border="0"
        />
      </div>

      <!-- About Container -->
      <div class="w3-container" id="about">
        <div class="w3-content" style="max-width: 700px">
          <h5 class="w3-center w3-padding-64">
            <span class="w3-tag w3-wide">ABOUT THE COVID-19</span>
          </h5>
          <p>
            New coronavirus disease or COVID-19 Caused by the corona virus
            Sarkowi-2 (SAR-CoV-2) is the transmission of the virus from person
            to person. by receiving droplets from coughing or sneezing Contact
            with secretions such as saliva, mucus, sputum, etc.
          </p>

          <div class="w3-panel w3-leftbar w3-light-grey">
            <p>COVID-19 vaccine</p>
            <p>
              <i
                >Usually when all kinds of germs enter the body. The body has a
                number of ways to deal with infection. One of these, Macrophage
                leukocytes, ingests the infection and leaves some remnants of
                the infection known as an antigen. The body recognizes the
                antigen as a foreign body and produces antibodies to deal with
                it. Including another type of white blood cells that remember
                that this pathogen is a foreign body. If infected in the future,
                the body will be able to recognize and manage it. The vaccine
                works the same way.
              </i>
            </p>
          </div>
        </div>
      </div>
    </div>
  </body>
</template>

<style>
body,
html {
  height: 100%;
  font-family: 'Inconsolata', sans-serif;
}
.about {
  margin-left: 10%;
  margin-right: 10%;
}

.menu {
  display: none;
}
</style>
