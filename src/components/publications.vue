<template>
    <section id="publications">
        <div class="container clarkBorderBottom">
            <h2>Publications</h2>
            <div class="accordion" role="tablist">
                <b-card no-body class="mb-1">
                    <b-card-header header-tag="header" class="p-1" role="tab">
                        <b-button block v-b-toggle.accordion-1 variant="dark">2013</b-button>
                    </b-card-header>
                    <b-collapse id="accordion-1" visible accordion="my-accordion" role="tabpanel">
                        <b-card-body>
                            <b-card-text>{{ text }}</b-card-text>
                        </b-card-body>
                    </b-collapse>
                </b-card>

                <b-card no-body class="mb-1">
                    <b-card-header header-tag="header" class="p-1" role="tab">
                        <b-button block v-b-toggle.accordion-2 variant="dark">2012</b-button>
                    </b-card-header>
                    <b-collapse id="accordion-2" accordion="my-accordion" role="tabpanel">
                        <b-card-body>
                            <p>
                                C.C. Cook, A. Kim, S. Terao, A.Gotoh, and M. Higuchi.  Consumption
                                of oxygen: a mitochondrial-generated progression signal of advanced cancer.
                                Cell Death and Disease, 3, e258.
                            </p>
                            <p>
                                C.C. Cook and M. Higuchi.  The awakening of an advanced malignant cancer: an insult
                                to the mitochondrial genome.  Biochimica et Biophysica Acta, 1820(5), 652.
                            </p>
                        </b-card-body>
                    </b-collapse>
                </b-card>

                <b-card no-body class="mb-1">
                    <b-card-header header-tag="header" class="p-1" role="tab">
                        <b-button block v-b-toggle.accordion-3 variant="dark">2008</b-button>
                    </b-card-header>
                    <b-collapse id="accordion-3" accordion="my-accordion" role="tabpanel">
                        <b-card-body>
                            <b-card-text>{{ text }}</b-card-text>
                        </b-card-body>
                    </b-collapse>
                </b-card>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: "publications",
        data() {
            return {
                text: `PhD Dissertation, UAMS.
Title: The ‘re-awakening’ of a mitochondrial-generated progression
signal in the development of advanced cancer.

        `
            }
        }
    }
</script>

<style scoped>
    #publications {
        padding-top: 60px;
    }

</style>