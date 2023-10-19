<template>
    <v-card height="100%">
        <v-alert
    type="warning"
    title="Ayúdanos a salvar vidas"
    text="Tu generosidad puede hacer una gran diferencia en la capacidad de los bomberos voluntarios para proteger a las personas y propiedades en momentos de crisis."
    
  ></v-alert>
        <Carrousel />
        <v-card-text>
            <v-row>
                <v-col cols="12" md="4">
                    <v-card height="400">
                        <v-card-title>Publicación 1</v-card-title>  
                    </v-card>
                </v-col>
                <v-col cols="12" md="4">
                    <v-card height="400">
                        <v-card-title>Publicación 2</v-card-title>
                    </v-card>
                </v-col>
                <v-col cols="12" md="4">
                    <v-card height="400">
                        <v-card-title>Publicación 3</v-card-title>
                    </v-card>
                </v-col>
            </v-row>
        </v-card-text>
    </v-card>
</template>

<script>
import Carrousel from '../components/Carrousel.vue'

export default {
    name: 'HomePage',
    components: {
        Carrousel
    }
}
</script>

<style lang="scss" scoped>

</style>