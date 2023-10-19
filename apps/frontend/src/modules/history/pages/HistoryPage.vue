<template>
    <v-card height="100%" elevation="0">
        <history-component />
        <photos-component></photos-component>
    </v-card>
</template>
<script>
import HistoryComponent from '../components/HistoryComponent.vue';
import photosComponent from '../components/photosComponent.vue';

export default {
    name: 'HistoryPage',
    components : {
        HistoryComponent,
        photosComponent,
        
    },
    data(){
        return{
           
        }
    }

}
</script>