<template>
    <v-row class="mt-5">
        <v-col cols="12" class="text-center">
            <v-btn color="primary" variant="text" :active="section==='contact'"
                @click="section='contact'"
            >Contacto</v-btn>
            <v-btn 
                color="primary" variant="text" :active="section==='history'"
                @click="section='history'"    
            >Historia</v-btn>
            <v-btn color="primary" variant="text" :active="section==='donations'"
                @click="section='donations'"
            >Donaciones</v-btn>
        </v-col>
        <v-col cols="12">
            <contact-administration v-if="section==='contact'"/>
        </v-col>
    </v-row>
</template>

<script>
    import ContactAdministration from './ContactAdministration.vue'

    export default {
        name: 'AdminComponent',
        components: {
            ContactAdministration
        },
        data: () => ({
            section: 'contact'
        })
    }
</script>

<style lang="scss" scoped>

</style>