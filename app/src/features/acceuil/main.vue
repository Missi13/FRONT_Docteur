<template>
    <v-container fluid class="container">
        <!--entete-->
        <v-row class="navbarHaut">
        </v-row>

        <!--contenu-->
        <v-row class="contenu d-flex flex-row justify-space-between">
            <v-col cols="3" class="contenuGauche">
                <navbar/>
            </v-col>

            <v-col cols="9" class="contenuDroite">
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
import navbar from "@/components/navbar-components/app-navbar.vue"
export default {
    name: 'MonAcceuil',
    data(){
        return{

        }
    },

    components:{
        navbar
    },

}
</script>

<style scoped>

    .container{
        min-height: 100vh;
        background-color: #eaf8bf;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
    }

    .navbarHaut{
        background-color: #335c67;
        max-height: 10vh
    }

    .contenu{
         
    }

    .contenuGauche{
        background-color: aliceblue;
        border: solid 1px #335c67;
        border-radius: 0 10px 10px 0;
    }

    .contenuDroite{
        background-color: aliceblue;
        border: solid 1px #335c67;
        border-radius: 10px 0 0 10px;
    }

</style>
