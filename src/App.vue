<template>
  <div id="app">
    <Navbar></Navbar>
    <router-view/>
    <MedzoarFooter></MedzoarFooter>
  </div>
</template>

<style>
  h1 {
    /*color: #fdfdfd;*/
    color: #434343;
    font-family: 'Source Serif Pro', Georgia, serif;
    font-size: 250%;
    text-align: center;
  }
  h2, h3 {
    font-family: 'Source Serif Pro', Georgia, serif;
    font-weight: lighter;
    color: #434343;
    text-align: center;
  }

  .card p {
    color: #434343;
    font-family: 'Nunito', "Lucida Console", sans-serif;
    font-size: 1.5em;
  }

  .card {
    /*padding: 5px;*/
    margin-top: 40px;
  }
  /*body {*/
  /*    color: #333;*/
  /*    font-family: 'Nunito', "Lucida Console", sans-serif;*/
  /*}*/

  p, dd, dt, #medzoarFooter h6, .clarkLikeParagraph, th, td {
    color: #434343;
    font-family: 'Nunito', "Lucida Console", sans-serif;
    font-size: 1.5em;
  }

  #medzoarFooter h6 {
    color: #fdfdfd;

  }

  #medzoarFooter {
    background-color: #434343;
  }

  #headShotDiv {
    background-color: #434343;
    border-radius: 50%;
    margin-bottom: 20px;
  }

  #headShotImg {
    border-radius: 50%;
  }

  /*#home img {*/
  /*    box-shadow: 4px 4px 4px #434343;*/
  /*}*/

  body {
    background-color: #fdfdfd;
    padding-top: 80px;
  }

  #socialContainer {

    border-bottom: 2px solid #434343;

  }

  .clarkBorderBottom {
    margin-top: 20px;
    margin-bottom: 40px;
    border-bottom: 2px solid #434343;
    padding-bottom: 40px;
  }

  .homeh1wrap, #icons {
    margin-top: 20px;
    margin-bottom: 20px;
    border-bottom: 2px solid #434343;
    padding-bottom: 10px;
  }

  #detailsList {
    text-align: center;
  }

  /* ------ Helper Classes -------*/
  .visuallyhidden {
    border: 0;
    clip: rect(0 0 0 0);
    height: 1px;
    margin: -1px;
    overflow: hidden;
    padding: 0;
    position: absolute;
    width: 1px;
    white-space: nowrap; /* 1 */
  }

  #home p {
    text-align: justify;
  }

  dt{
    padding: 10px 0;
    border-bottom:1px solid #434343;
  }

  dd{
    margin-bottom: 20px;
  }

  .iconContainer {
    text-align: center;

    border-radius: 50%;
    transition: .5s;
    margin: 10px 30px;
    padding: 20px 20px;

  }

  #icons{
    text-align: center;
    /*background-color: #314551;*/
    padding-top: 40px;

  }

  #social {
    margin-top: 40px;
    border-top: 3px solid #434343;

  }

  .icon{
    font-size: 3.5em;
    color: #434343;
    text-shadow: 1px 1px 1px #434343;
  }


</style>

<script>
  import navbar from "./components/navbar";
  import medzoarFooter from "./components/footer"
  export default {
    components: {
      'MedzoarFooter': medzoarFooter,
      'Navbar': navbar
    }
  }
</script>