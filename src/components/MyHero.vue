<template>
    <v-container>
        <v-row class="d-flex align-center mx-10" >
            <v-col lg="8">
                <h1 class="hello">Hello!</h1>
                <h2 class="name">I'm <b class="name">Md. Anik Khan</b></h2>
                <h4 class="intro">Web Designer & Font-end Developer</h4>
                <v-btn class="resume-btn mt-5" outlined="success">MY RESUME</v-btn>
                <v-icon></v-icon>
            </v-col>
            <v-col lg="4">
                <img width="100%" src="../assets/hero.svg">
            </v-col>
        </v-row>
    </v-container>
  
</template>

<script>
export default {

}
</script>

<style>
    h1.hello {
        font-size: 40px;
        font-family: monospace;
    }
    h2.name {
        font-size: 55px;
        color: grey;
    }
    b.name{
        color:#4CAF50;
    }
    h4.intro {
    font-size: 25px;
    font-weight: 300;
    }
    button.resume-btn.mt-5.v-btn.v-btn--outlined.theme--light.v-size--default {
    outline: auto;
    outline-color: #4CAF50;
    font-size: 15px;
    font-weight: 900;
    background-color: white;
    color:#4CAF50;
}

</style>