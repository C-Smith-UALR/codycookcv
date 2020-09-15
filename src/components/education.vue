<template>
    <section id="education" class="mt-5">
        <div class="container clarkBorderBottom">
            <h2>Education</h2>

            <table>
                <thead>
                <tr>
                    <th>Degree</th>
                    <th>Subject</th>
                    <th>University</th>
                    <th>Start Date</th>
                    <th>End Date</th>
                </tr>
                </thead>
                <tbody>
                <tr class="clarkNotHead">
                    <td>BS*</td>
                    <td>Biology</td>
                    <td>UCA, Conway, AR</td>
                    <td>7/1/2001</td>
                    <td>6/30/2005</td>
                </tr>
                <tr class="clarkNotHead">
                    <td>MD</td>
                    <td>Medicine</td>
                    <td>UAMS, Little Rock, AR</td>
                    <td>7/1/2005</td>
                    <td>6/30/2016</td>
                </tr>
                <tr class="clarkNotHead">
                    <td>Ph.D</td>
                    <td>Biochemistry and Molecular Biology</td>
                    <td>UAMS</td>
                    <td>7/1/2005</td>
                    <td>6/30/2011</td>
                </tr>


                </tbody>
            </table>
            <small class="text-muted">
                *Valedictorian, Summa Cum Laude
            </small>
        </div>

    </section>
</template>

<script>
    export default {
        name: "education"
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

    #education {
        padding-top: 60px;
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

        #education {
            padding-top: 60px;
        }

        td:nth-of-type(1):before { content: "Degree"; }
        td:nth-of-type(2):before { content: "Subject"; }
        td:nth-of-type(3):before { content: "University"; }
        td:nth-of-type(4):before { content: "Start Date"; }
        td:nth-of-type(5):before { content: "End Date"; }


    }

</style>