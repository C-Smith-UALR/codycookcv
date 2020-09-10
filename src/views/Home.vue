<template>
  <div class="home">
    <div class="homeh1wrap">
      <h1 id="homeName">Curriculum Vitae</h1>
    </div>
    <div class="container">
      <div class="row" itemscope itemtype="http://schema.org/Person">
        <div class="col-sm-12 col-lg-6">
          <h2 class="visuallyhidden">Personal Details</h2>
          <div id="headShotDiv" style="text-align: center">
            <img id="headShotImg" src="../../public/Cody-Picture-Transparent-Cropped-Square.png" alt="professional photograph of Cody Chase Cook"
                 class="img-fluid" itemprop="image">
          </div>

          <p itemprop="description" style="text-align: justify">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
            Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          </p>
        </div>
        <div class="col-sm-12 col-lg-6 pt-3" id="detailsList">
          <dl>
            <dt>Name</dt>
            <dd itemprop="name">
              <span itemprop="givenName">Cody</span> Chase <span itemprop="familyName">Cook</span>, Ph.D
            </dd>
            <dt>Date of Birth</dt>
            <dd itemprop="birthDate">
              <time datetime="1983-09-12">9/12/1983</time>
            </dd>
            <dt>Nationality</dt>
            <dd itemprop="nationality">
              United States
            </dd>
            <dt>Location</dt>
            <dd itemprop="homeLocation">Tennessee</dd>
            <dt>Telephone</dt>
            <dd>
              <a itemprop="telephone" href="tel:5012583079">
                501.258.3079
              </a>
            </dd>
            <dt>Email</dt>
            <dd>
              <a itemprop="email" href="mailto:cody.cook@gmail.com?subject=Resume&body=I saw your resume online.">
                cody.cook@gmail.com
              </a>
            </dd>
            <dt>Address</dt>
            <dd itemprop="address" itemscope itemtype="http://schema.org/PostalAddress">
              <span itemprop="streetAddress">
                62 North Main St,
                Apt 1001,
              </span>
              <span itemprop="addressLocality">Memphis, </span>
              <span itemprop="addressRegion">TN, </span>
              <span itemprop="addressCountry">USA</span>
            </dd>


          </dl>
        </div>
      </div> <!--row-->
    </div> <!--container-->
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  data () {
    return {
      publicPath: process.env.BASE_URL
    }
  },

}
</script>
