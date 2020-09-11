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
            Dr. Cody Chase Cook is the Founder, President, and Chief Medical Scientist at MitoGene and
            HTWO Beverage Company&#8482;.  This is his professional curriculum vitae.  He is not married and has
            no children, choosing to focus intently on his career.
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
    <icons></icons>
    <education></education>
    <experience></experience>

  </div><!--home-->

</template>

<script>
// @ is an alias to /src
import icons from '../components/icons'
import education from '../components/education'
import experience from "../components/experience";

export default {
  name: 'Home',
  data () {
    return {
      publicPath: process.env.BASE_URL
    }
  },
  components: {
    'Icons':icons,
    'Education': education,
    'Experience': experience
  }

}
</script>
