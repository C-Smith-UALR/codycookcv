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
                    <td>UAMS</td>
                    <td>Family Medicine Resident</td>
                    <td>7/1/2009</td>
                    <td>6/30/2012</td>
                    <td>Little Rock, AR</td>
                </tr>
                <tr class="clarkNotHead">
                    <td>UAMS</td>
                    <td>Palliative Medicine Fellow</td>
                    <td>7/1/2012</td>
                    <td>6/30/2013</td>
                    <td>Little Rock, AR</td>
                </tr>
                <tr class="clarkNotHead">
                    <td>Arkansas Hospice</td>
                    <td>Medical Director</td>
                    <td>7/1/2013</td>
                    <td>4/15/2016</td>
                    <td>Little Rock, AR</td>
                </tr>
                <tr class="clarkNotHead">
                    <td>UAMS</td>
                    <td>Assistant Professor</td>
                    <td>4/16/16</td>
                    <td>10/31/2017</td>
                    <td>Little Rock, AR</td>
                </tr>
                <tr class="clarkNotHead">
                    <td>Arkansas Hospice</td>
                    <td>Medical Director</td>
                    <td>1/1/2018</td>
                    <td>7/31/2020</td>
                    <td>Little Rock, AR</td>
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




        td:nth-of-type(1):before { content: "Organization"; }
        td:nth-of-type(2):before { content: "Position"; }
        td:nth-of-type(3):before { content: "Start Date"; }
        td:nth-of-type(4):before { content: "End Date"; }
        td:nth-of-type(5):before { content: "Location"; }


    }

</style>