<template>
    <v-container>
        <div class="skills d-inline pa-1 green white--text">
            <v-icon left size="30px" color="white">
                mdi-checkbox-marked-circle
            </v-icon>
            Skills
        </div>
        <v-row class="py-5">
            <v-col lg="6">
                <v-list>
                    <v-list-item-group>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">Wordpress Knowledge</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="90%" class="progress">90%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">Wordpress Theme Customization</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="80%" class="progress">80%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">HTML/CSS/BOOTSTRAP</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="85%" class="progress">85%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">OOP (Object Oriented Programming)</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="70%" class="progress">70%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">ReactJs</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="70%" class="progress">70%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">Python(Basic)</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="70%" class="progress">70%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                    </v-list-item-group>
                </v-list>
            </v-col>
            <v-col lg="6">
                <v-list>
                    <v-list-item-group>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">Database Managment</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="85%" class="progress">85%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">Graphics Design</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="90%" class="progress">90%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">Adobe Photoshop</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="85%" class="progress">85%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">Adobe Illustator</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="70%" class="progress">70%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">Communication Skils</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="95%" class="progress">95%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                        <v-list-item>
                            <v-list-item-icon>
                                <v-icon>mdi-send</v-icon>
                            </v-list-item-icon>
                            <v-list-item-content>
                                <v-list-item-title class="py-1">Team Work</v-list-item-title>
                                <v-progress-linear color="green" height="15" value="95%" class="progress">95%</v-progress-linear>
                            </v-list-item-content>
                        </v-list-item>
                    </v-list-item-group>
                </v-list>
            </v-col>
        </v-row>
  </v-container>
</template>

<script>
  export default {
       
};
</script>

<style>
    .skills{
        font-size: 30px;
        font-weight: 700;
    }
    .v-progress-linear__content {
    align-items: center;
    display: flex;
    height: 100%;
    left: 0;
    justify-content: center;
    position: absolute;
    top: 0;
    width: 100%;
    font-size: 15px;
    color: white;
    font-weight: 500;
    }
    .v-icon.v-icon {
    align-items: center;
    display: inline-flex;
    font-feature-settings: "liga";
    font-size: 24px;
    justify-content: center;
    letter-spacing: normal;
    line-height: 1;
    position: relative;
    text-indent: 0;
    transition: 0.3s cubic-bezier(0.25, 0.8, 0.5, 1), visibility 0s;
    vertical-align: middle;
    -webkit-user-select: none;
    -moz-user-select: none;
    user-select: none;
    color: green;
    }
    .v-list-item__title.py-1 {
    font-size: 18px;
    color: black;
    font-weight: 500;
    }

</style>