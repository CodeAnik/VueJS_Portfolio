<template>
    <v-container id="aboutme">
        <div class="about d-inline pa-1 green white--text">
            <v-icon left size="30px" color="white">
                mdi-checkbox-marked-circle
            </v-icon>
            About Me
        </div>
        <v-row  class="d-flex align-center mx-10">
            <v-col lg="8">
                <h3><b>Hey there!</b></h3>
                <p class="description">
                    Hello! I'm a web Developer & Designer. My name us Anik Khan, and I'm freshman studying Computer Science & Engineering at University of Asia Pacific(UAP),Dhaka.
                </p>
                <p class="description">
                    I love to solve problems. Whether it's finding the most elegant way to write a line of code or figuring out which chord fits best into a progression. I love the challenge of finding a way and discovering solutions. Maybe that's why I love writing and the satisfaction that comes from finding just the rignt word. I build open source projects and write the missing instruction manuals of the web.
                </p>
            </v-col>
            <v-col lg="4">
                <img width="100%" src="../assets/aboutme.png">
            </v-col>
        </v-row>
        <v-row class="mx-10">
            <h3 class="overview"><b>OVERVVIEW</b></h3>
            <p class="description">I looking for challenging problems to solve. Now I still is in enterprise software development, Web development, UI/UX design, Graphics Design, Web Design. however, I have an insatiable curiosity for AI – particularly deep learning – applications and their potential to change the technology landscape.</p>
            <p class="description">I like building awesome software or web Develop & Design. I've built websites, browser plugins, corporate software, Web design, App design and even Graphics Design. If you are interested, you can view some of my favorite projects in my portfolio.</p>
            
            <h3 class="interest"><b>INTERESTS</b></h3>
            <p class="description">I HAVE A LARGE INTEREST IN PROGRAMMING AND I ENJOY APPLYING MY SKILLS TO MY PERSONAL PROJECTS. FOND OF DATA ENGINEERING, FULL STACK DEVELOPMENT, MACHINE LEARNING, COMPUTER VISION & DESIGNING.</p>
            <p class="description">I've worked with a wide variety of programming languages. For web applications I use PHP and Javascript. Whenever I need the most performance possible I obviously go with C++ and finally when I am building prototypes or working on my hobby projects I fall back on Python.</p>
        </v-row>
    </v-container>
  
</template>

<script>
export default {

}
</script>

<style>  
    .about{
    font-size: 30px;
    font-weight: 700;
    }
    p.description {
    text-align: justify;
}
</style>