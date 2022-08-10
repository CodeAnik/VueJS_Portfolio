<template>
    <v-footer color='success'>
            <v-row justify="center">
                    <v-btn v-for="icon in icons" :key="icon" class="mx-4 mt-5 white--text center" icon>
                    <v-icon size="24px">
                    {{ icon }}
                    </v-icon>
                    </v-btn>
                    <v-subheader class="white--text center">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laboriosam maiores, cupiditate sapiente voluptatum voluptate hic nam assumenda velit molestiae explicabo.</v-subheader>
                    <p>This website copyright @<b>Md. Anik Khan</b></p>
            </v-row>
  </v-footer>
</template>

<script>
export default {
    name: 'MyFooter',
    data(){
        return{
            icons: [
                'mdi-facebook',
                'mdi-twitter',
                'mdi-linkedin',
                'mdi-instagram',
            ],
        }
    }
    
}
</script>

<style>

</style>