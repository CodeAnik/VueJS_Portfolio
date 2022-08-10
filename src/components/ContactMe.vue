<template>
<v-container>
        <div class="contact d-inline pa-1 green white--text">
            <v-icon left size="30px" color="white">
                mdi-checkbox-marked-circle
            </v-icon>
            Contact With Me
        </div>
        <v-row justify="center mx-10">
            <v-col lg="12" class="text-center">
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Veritatis consectetur, quisquam nobis et sapiente, minus fugit similique voluptatibus ipsum, laboriosam a explicabo quis rerum? Saepe quod officiis numquam repellat omnis?</p>
            </v-col>
        </v-row>
        <v-row class="py-10">
            <v-col lg="6">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d7302.119724945685!2d90.35425382603134!3d23.780882556213314!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3755c0be89363e87%3A0x3795036c15355c82!2sKallyanpur%2C%20Dhaka!5e0!3m2!1sen!2sbd!4v1660046861184!5m2!1sen!2sbd" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </v-col>
            <v-col lg="6">
                    <v-form ref="form">
                    <v-text-field
                    v-model="contactInfo.name"
                    :counter="10"
                    label="Name"
                    required
                    ></v-text-field>

                    <v-text-field
                    v-model="contactInfo.email"
                    label="E-mail"
                    required
                    ></v-text-field>
                    <v-textarea label="Message" v-model="contactInfo.message">

                    </v-textarea>

                    <v-btn color="success" class="mr-4">
                        Send
                    </v-btn>
                </v-form>
            </v-col>
        </v-row>
        
    </v-container>
    
</template>

<script>
export default {
    name: 'ContactMe',
    data(){
        return{
            contactInfo:{}
        }
    }
    
}
</script>

<style>
    .contact{
    font-size: 30px;
    font-weight: 700;
    }

</style>