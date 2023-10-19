<template>
    <div>
        <v-row>
            <v-col cols="3">
                <h4 class="mt-4">
                    Necesitamos su apoyo para mantener unidades de emergencia, comprar equipos y garantizar servicios básicos para los Bomberos Voluntarios de Lanús. Nuestra misión es fortalecer la seguridad, cuidar a los bomberos y promover la participación de la comunidad en la protección local.
                </h4>
            </v-col>
            <v-col cols="6">
                <v-row align="center" justify="center">
                    <v-col cols="12" md="6" class="text-center">
                        <h3 class="mb-4">¡Escaneá el QR y doná!</h3>
                        <v-img class="mx-auto" width="200" height="200" cover src="../../assets/qr.png"></v-img>
                    </v-col>
                    <v-col cols="12" md="6">
                        <h2 class="mb-4 text-center">Datos de transacción</h2>
                        <v-text-field variant="outlined" label="Alias" readonly :model-value="alias" />
                        <v-text-field variant="outlined" label="Nombre" readonly :model-value="name" />
                        <v-text-field variant="outlined" label="CBU" readonly :model-value="cbu" />
                    </v-col>
                </v-row>
            </v-col>
            <v-col cols="3">
                <h4 class="mt-4">
                    solicita ayuda para mantener las operaciones de Bomberos Voluntarios de Lanús, que incluyen equipos, servicios básicos y apoyo a los bomberos. Su objetivo es mejorar la seguridad, el bienestar de los bomberos y la participación comunitaria en la protección.
                </h4>
            </v-col>
        </v-row>
    </div>
</template>

<script>
    export default {
        name: 'Donations-Component',
        data: () => ({
            instagram: false,
            alias: 'bomberos.lanus.mp',
            name: 'Bomberos Voluntarios Lanús',
            cbu: '0000003100076208932278',
            rating: 0,
            message: '',
            messageRule: [
                v => !!v || 'Este campo es obligatorio',
                v => v.length < 50 || 'El mensaje debe tener menos de 50 caracteres'
            ],
            formValue: true,
        })
    }
</script>

<style lang="scss" scoped>

</style>