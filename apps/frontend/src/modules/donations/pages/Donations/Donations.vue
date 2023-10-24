<template>
     <div>
        <v-row>
    <v-col cols="6">
       <v-card width="600px" 
       color="red"
       variant="tonal">
      <v-card-title class="text-h6 text-md-h5 text-lg-h4">¡Ayúdanos a salvar vidas!</v-card-title>
      <v-card-text>
        Tu generosidad puede proporcionarles los medios, la capacitación y los recursos
        que requieren para continuar su trabajo con compromiso y excelencia.
        Cada aporte, sin importar cuán pequeño, marca un gran impacto en la seguridad de todos.
        ¡Haz tu donación ahora y respalda a nuestros bomberos!
  </v-card-text>
    </v-card>
  
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
     <v-img
      src="../../assets/bombero.JPG"
      height="300px"
      width="200px"
      cover
    ></v-img>
 </v-col>
 <v-col cols="3">
   <v-img
   src="../../assets/bombero2.JPG"
   heigth="200px"
   width="300px"
   cover>
</v-img>
<v-col cols="12">
<v-alert
    color="error"
    text="'Ninguno de nosotros solos es tan bueno como todos nosotros juntos'">
</v-alert> </v-col>
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