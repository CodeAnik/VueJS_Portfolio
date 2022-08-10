<template>
    <v-container>
        <div class="portfolio d-inline pa-1 green white--text">
            <v-icon left size="30px" color="white">
                mdi-checkbox-marked-circle
            </v-icon>
            Portfolio
        </div>
        <v-row justify="center mx-10">
            <v-col lg="12" class="text-center">
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Veritatis consectetur, quisquam nobis et sapiente, minus fugit similique voluptatibus ipsum, laboriosam a explicabo quis rerum? Saepe quod officiis numquam repellat omnis?</p>
            </v-col>
            <v-col lg="12">
                <div class="text-center">
                    <v-chip @click="activePortfolio = 'webDevs'" :color="activePortfolio == 'webDevs'? 'success':''" class="mx-5">Web Development</v-chip>
                    <v-chip @click="activePortfolio = 'gs'" :color="activePortfolio == 'gs'? 'success':''" class="mx-5">Graphic Design</v-chip>
                    <v-chip @click="activePortfolio = 'UiUx'" :color="activePortfolio == 'UiUx'? 'success':''" class="mx-5">UI/UX Design</v-chip>
                </div>
            </v-col>
            <slot v-if="activePortfolio == 'webDevs'">
                <v-col lg="3" v-for="(web,webindex) in webDevs" :key='webindex'>
                <v-card>
                    <v-img
                    :src="web.image"
                    class="white--text align-end"
                    gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                    height="200px"
                    >
                    <v-card-title>{{web.title}}</v-card-title>
                    </v-img>
                </v-card>
            </v-col>
            </slot>
            <slot v-if="activePortfolio == 'gs'">
                <v-col lg="3" v-for="(gs,gsindex) in gs" :key='gsindex'>
                <v-card>
                    <v-img
                    :src="gs.image"
                    class="white--text align-end"
                    gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                    height="200px"
                    >
                    <v-card-title>{{gs.title}}</v-card-title>
                    </v-img>
                </v-card>
            </v-col>
            </slot>
            <slot v-if="activePortfolio == 'UiUx'">
                <v-col lg="3" v-for="(UiUx,UiUxindex) in UiUx" :key='UiUxindex'>
                <v-card>
                    <v-img
                    :src="UiUx.image"
                    class="white--text align-end"
                    gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                    height="200px"
                    >
                    <v-card-title>{{UiUx.title}}</v-card-title>
                    </v-img>
                </v-card>
            </v-col>
            </slot>
        </v-row>
    </v-container>
  
</template>

<script>
export default {
    name: 'MyPortfolio',
    data(){
        return{
            activePortfolio: 'webDevs',
            webDevs:[
                {title: 'Web Development 1', image:'https://www.datasciencecentral.com/wp-content/uploads/2021/10/8924472301.jpeg'},
                {title: 'Web Development 2', image:'https://www.kindpng.com/picc/m/145-1455678_making-websites-web-development-services-hd-png-download.png'},
                {title: 'Web Development 3', image:'https://png.pngitem.com/pimgs/s/112-1127806_sahyadri-technologies-web-application-development-png-transparent-png.png'},
                {title: 'Web Development 4', image:'https://www.designer-daily.com/wp-content/uploads/2020/03/web-dev-business.jpg'},
                {title: 'Web Development 5', image:'https://www.vocso.com/blog/wp-content/uploads/2022/04/Top-Web-Development-Tools.jpg'}
            ],
            gs:[
                {title: 'Graphics Design 1', image:'https://visme.co/blog/wp-content/uploads/2021/10/what-is-graphic-design-header-1200.png'},
                {title: 'Graphics Design 2', image:'data:image/png;base64,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'},
                {title: 'Graphics Design 3', image:'https://i.ytimg.com/vi/0e23zYANdaQ/maxresdefault.jpg'},

            ],
            UiUx:[
                {title: 'UI/UX Design 1', image:'https://fiverr-res.cloudinary.com/images/q_auto,f_auto/gigs/124179558/original/36c2fe76d10b2f1e3d6ff81e5606489e059312a0/create-amazing-ui-ux-designs-for-mobile-apps.png'},
                {title: 'UI/UX Design 2', image:'https://appinventiv.com/wp-content/uploads/sites/1/2019/02/How-Important-is-UI-UX-Design-in-an-App-Development-Process.png'},
            ]
        }
    }
}
</script>

<style>
    .portfolio {
    font-size: 30px;
    font-weight: 700;
    }
    h1.portfolio {
        text-decoration: underline;
        text-decoration-color: chocolate;
        color: chocolate;
    }

</style>