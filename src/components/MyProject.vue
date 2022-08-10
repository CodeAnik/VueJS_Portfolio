<template>
    <v-container class="my-5">
        <div class="project d-inline pa-1 green white--text">
            <v-icon left size="30px" color="white">
                mdi-checkbox-marked-circle
            </v-icon>
            Projects
        </div>
        <v-col lg="12" class="text-center">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Veritatis consectetur, quisquam nobis et sapiente, minus fugit similique voluptatibus ipsum, laboriosam a explicabo quis rerum? Saepe quod officiis numquam repellat omnis?</p>
        </v-col>
        <v-row justify="center mx-10">
            <v-col lg="4" v-for="project in 3" :key="project">
                <v-card class="mx-auto" max-width="374">
                <v-img height="250" src="../assets/web1.png"></v-img>

            <v-card-title>Web Development</v-card-title>
            <v-card-text>
                <p class='description'>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio similique labore enim praesentium obcaecati optio? Delectus sint aliquid ducimus assumenda?</p>
            </v-card-text>
                <v-divider class="mx-4"></v-divider>
                <v-card-actions>
                    <v-btn color="success">View Details</v-btn>
                    <v-spacer/>
                    <v-rating
                        :value="4.5"
                        color="amber"
                        dense
                        half-increments
                        readonly
                        size="14"
                        ></v-rating>
                </v-card-actions>
            </v-card>
        </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default {
    
}
</script>
<style scoped>
    .project{
    font-size: 30px;
    font-weight: 700;
    }
    p.description{
        text-align: justify;
    }
</style>