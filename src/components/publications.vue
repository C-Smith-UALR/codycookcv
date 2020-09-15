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
                                C.C. Cook, A. Kim, S. Terao, A. Gotoh, and M. Higuchi.  Consumption
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
                            <b-card-text>
                                A. Naito, C. Cook, T. Mizumachi, M. Wang, C. Xie, T. Evans, T. Kelley,
                                and M. Higuchi.  Progressive tumor features accompany epithelial-mesenchymal
                                transition induced in mitochondrial DNA depleted cells.  Cancer Science, 99(8): 1584
                            </b-card-text>
                        </b-card-body>
                    </b-collapse>
                </b-card>

                <b-card no-body class="mb-1">
                    <b-card-header header-tag="header" class="p-1" role="tab">
                        <b-button block v-b-toggle.accordion-4 variant="dark">2006</b-button>
                    </b-card-header>
                    <b-collapse id="accordion-4" accordion="my-accordion" role="tabpanel">
                        <b-card-body>
                            <b-card-text>
                                D.R. Pierce, C.C. Cook, J.A. Hinson, and K.E. Light.  Are oxidative mechanisms
                                primary in ethanol induced purkinje neuron death of the neonatal rat?  Neuroscience
                                Letters, 400(1-2), 130
                            </b-card-text>
                        </b-card-body>
                    </b-collapse>
                </b-card>

                <b-card no-body class="mb-1">
                    <b-card-header header-tag="header" class="p-1" role="tab">
                        <b-button block v-b-toggle.accordion-5 variant="dark">2005</b-button>
                    </b-card-header>
                    <b-collapse id="accordion-5" accordion="my-accordion" role="tabpanel">
                        <b-card-body>
                            <b-card-text>
                                Cook, C., Haley, U.B. and Runge, S.W.  Acidification Induced Exocytic Response in
                                MCF-7 Cells and Correlating Apoptosis.  Arkansas BRIN Research Conference. Little Rock,
                                AR.
                            </b-card-text>
                            <b-card-text>
                                UCA Honors College Dissertation.  Title: The evolution of the art of fly-tying: How scientific,
                                social, and industrial revolutions of the Victorian age influenced the art of fly-tying.
                            </b-card-text>
                        </b-card-body>
                    </b-collapse>
                </b-card>
                <b-card no-body class="mb-1">
                    <b-card-header header-tag="header" class="p-1" role="tab">
                        <b-button block v-b-toggle.accordion-6 variant="dark">2004</b-button>
                    </b-card-header>
                    <b-collapse id="accordion-6" accordion="my-accordion" role="tabpanel">
                        <b-card-body>
                            <b-card-text>
                                D.R. Pierce, C.C. Cook, J.A. Hinson, and K.E. Light.  Are oxidative mechanisms primary in ethanol induced purkinje
                                neuron death of the neonatal rate?  Alcoholism: Clinical and Experimental Research, 28(86A)
                            </b-card-text>
                            <b-card-text>
                                H.R. Owens, V. Chen, C.C. Cook, D.R. Pierce, and K.E. Light.  Comparative ability of NMDA receptor
                                antagonists and ethanol in producing neurodegeneration of rat purkinje neurons during
                                postnatal vulnerable periods.  Alcoholism: Clinical and Experiemental Research, 28(86A)
                            </b-card-text>
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