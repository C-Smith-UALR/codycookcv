<template>
    <section id="navbar">
        <div>
            <b-navbar toggleable="lg" type="dark" variant="dark" fixed="top">
                <b-navbar-brand to="/">
                    <div class="clarkCenter">
                        <b>CC</b>
                    </div>
                </b-navbar-brand>

                <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
                <b-collapse id="nav-collapse" is-nav>
                    <b-navbar-nav class="ml-auto">
                        <b-nav-item to="/">home</b-nav-item>
                        <b-nav-item to="/mediums">mediums</b-nav-item>

                    </b-navbar-nav>


                </b-collapse>





            </b-navbar>
        </div>

    </section>
    
</template>

<script>
    export default {
        name: "navbar"
    }
</script>

<style scoped>
    .clarkCenter{
        background-color: #42b983;
        width: 50px;
        height: 50px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
    }

</style>