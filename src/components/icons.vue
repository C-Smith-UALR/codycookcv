<template>
    <div class="container" id="icons">
        <div class="row">
            <div class="col-sm col1 iconContainer">
                <a :href="`${publicPath}Curriculum-Vitae-Cody-Cook-2020.pdf`" download>
                    <i class="fa fa-file-pdf-o icon" aria-hidden="true"></i>

                </a>
                <div style="text-align: center" class="mt-3 clarkLikeParagraph">
                    Resume PDF
                </div>


            </div>

            <div class="col-sm col4 iconContainer">
                <a href="https://htwo.com/">
<!--                    <i class="fa fa-github icon" aria-hidden="true"></i>-->
                    <img src="../../public/HTWO.png" alt="HTWO HydrogenWater icon">

                </a>
                <div style="text-align: center" class="mt-3 clarkLikeParagraph">
                    HTWO Website
                </div>

            </div>

            <div class="col-sm col5 iconContainer">
                <a href="https://www.linkedin.com/in/cody-cook-07419940/">

                    <i class="fa fa-linkedin-square icon" aria-hidden="true"></i>

                </a>
                <div style="text-align: center" class="mt-3 clarkLikeParagraph">
                    LinkedIn Profile
                </div>
            </div>








        </div> <!-- row -->
    </div>  <!--container-->
</template>

<script>
    export default {
        name: "icons",
        data () {
            return {
                publicPath: process.env.BASE_URL
            }
        },
    }
</script>

<style scoped>

</style>