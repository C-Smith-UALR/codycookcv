<template>
    <section id="experience" class="mt-5">
        <div class="container clarkBorderBottom">
            <h2>Experience</h2>

            <table>
                <thead>
                <tr>
                    <th>Organization</th>
                    <th>Position</th>
                    <th>Start Date</th>
                    <th>End Date</th>
                    <th>Location</th>
                </tr>
                </thead>
                <tbody>
                <tr class="clarkNotHead">
                    <td>MitoGene</td>
                    <td>Founder and President</td>
                    <td>2010</td>
                    <td>present</td>
                    <td>Memphis, TN</td>
                </tr>
                <tr class="clarkNotHead">
                    <td>MitoGene</td>
                    <td>Chief Medical Scientist</td>
                    <td>2010</td>
                    <td>present</td>
                    <td>Memphis, TN</td>
                </tr>
                <tr class="clarkNotHead">
                    <td>HTWO Beverage Company</td>
                    <td>Founder and President</td>
                    <td>2013</td>
                    <td>present</td>
                    <td>Memphis, TN</td>
                </tr>
                <tr class="clarkNotHead">
                    <td>HTWO Beverage Company</td>
                    <td>Chief Medical Scientist</td>
                    <td>2013</td>
                    <td>present</td>
                    <td>Memphis, TN</td>
                </tr>

                </tbody>
            </table>
        </div>

    </section>
</template>

<script>
    export default {
        name: "experience"
    }
</script>

<style scoped>
    table {
        width: 100%;
        border-collapse: collapse;
    }

    .clarkNotHead:nth-of-type(odd) {
        background: #42b983;
    }

    th {
        background: #fdfdfd;
    }

    td, th {
        padding: 6px;
        text-align: left;
        border: 1px solid #434343;

    }

    /*  ////////////////////////////  queries //////////////////// */
    @media only screen and (max-width: 780px), (min-device-width: 768px) and (max-device-width: 1024px) {
        table, thead, tbody, th, td, tr {
            display: block;
        }

        thead tr {
            position: absolute;
            top: -9999px;
            left: -9999px;
        }

        tr {
            border: 1px solid #fdfdfd;
        }

        td {
            border: none;
            border-bottom: 1px solid #fdfdfd;
            position: relative;
            padding-left: 50%;
        }

        td:before {
            position: absolute;
            top: 6px;
            left: 6px;
            width: 45%;
            padding-right: 10px;
            white-space: nowrap;
        }

        #experience {
            padding-top: 60px;
        }


        td:nth-of-type(1):before { content: "Organization"; }
        td:nth-of-type(2):before { content: "Position"; }
        td:nth-of-type(3):before { content: "Start Date"; }
        td:nth-of-type(4):before { content: "End Date"; }
        td:nth-of-type(5):before { content: "Location"; }


    }

</style>