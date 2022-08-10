<template>
    <v-container class="py-5">
            <div class="education d-inline pa-1 green white--text">
            <v-icon left size="30px" color="white">
                mdi-checkbox-marked-circle
            </v-icon>
            Educational Qualifications
            </div>
        <v-col>
            <v-card-text class="py-0">
                <v-timeline align-top dense>
                    <v-timeline-item color="pink" small>
                        <v-row class="pt-1">
                            <v-col>
                                <h1>UNIVERSITY OF ASIA PACIFIC</h1>
                                <h3>B.Sc in Computer Science and Engineering</h3>
                                <h5>Duration: 4 Years (August 2017 TO March 2022)</h5>
                                <h5>CGPA: 3.03 (Out of 4.00) </h5>
                            </v-col>
                        </v-row>
                    </v-timeline-item>
                </v-timeline>
                <v-timeline align-top dense>
                    <v-timeline-item color="green" small>
                        <v-row class="pt-1">
                            <v-col>
                                <h1>SIRAJGANJ POLICE LINES SCHOOL & COLLEGE</h1>
                                <h3>Higher Secondary School Certificate (HSC)</h3>
                                <h3>Grourp: Science (June-2014 TO March-2016)</h3>
                                <h5>GPA: 4.00 (Out of 5.00) </h5>
                            </v-col>
                        </v-row>
                    </v-timeline-item>
                </v-timeline>
                <v-timeline align-top dense>
                    <v-timeline-item color="pink" small>
                        <v-row class="pt-1">
                            <v-col>
                                <h1>DASHURIA M. M. HIGH SCHOOL</h1>
                                <h3>Higher Secondary School Certificate (HSC)</h3>
                                <h3>Grourp: Science (January-2009 TO March-2014)</h3>
                                <h5>GPA: 4.81 (Out of 5.00) </h5>
                            </v-col>
                        </v-row>
                    </v-timeline-item>
                </v-timeline>
            </v-card-text>
        </v-col>
</v-container>
</template>

<script>
export default {
    
}
</script>

<style>
    .education{
        font-size: 30px;
        font-weight: 700;
    }

</style>