<template>
    <v-row align="center" justify="center" class="ma-4">
        <v-col cols="12" lg="6">
            <v-card elevation="10" class="pa-10">
                <v-row>
                    <v-col cols="12" lg="4"> 
                        <v-img cover height="400" src="../assets/iniciobomberos.jpg.jpeg"> </v-img> </v-col>
                    <v-col cols="12" lg="8">
                        <h2 :class="$vuetify.display.mdAndDown ? 'text-center' : 'text-start'">COMO EMPEZÓ TODO</h2>
                        <v-card-text :class="$vuetify.display.mdAndDown ? 'text-center' : 'text-start'">
                            Los inicios de esta sociedad se deben a que un incendio ocurrido en 1913 en Villa Sarmiento arrasó con todo a su paso, mientras los bomberos, que venían desde Avellaneda, llegaban tarde. Entonces un grupo de vecinos se decidió a fundar lo que hoy es Bomberos Voluntarios de Lanús.
                            Fue el 20 de septiembre de aquel año que los señores P. Rabboni, F. Medaglia, L. Monteverde, J. Sadocco, L. Civirani, L. Sioli y J. Grignaschi buscan la 'manera de salvaguardar de las calamidades a la comunidad'.
                        </v-card-text>
                    </v-col>
                </v-row>
            </v-card>
        </v-col>
        <v-col cols="12" lg="6">
            <v-card elevation="10" class="pa-10">
                <v-row>
                    <v-col cols="12" lg="4"> 
                        <v-img cover height="400" src="../assets/monumento.jpg"> </v-img> </v-col>
                    <v-col cols="12" lg="8">
                        <h2 :class="$vuetify.display.mdAndDown ? 'text-center' : 'text-start'">
                            MONUMENTO AL VALOR Y A LA SOLIDARIDAD
                        </h2>
                        <v-card-text :class="$vuetify.display.mdAndDown ? 'text-center' : 'text-start'">
                            En la avenida Eva Perón entre Pergamino y Luján, en la Plaza Güemes de Villa Obrera, los bomberos están desde septiembre de 2003 cabalmente representados en un impactante trabajo de la escultora Nilda Toledo Guma,
                        quien cuenta que la creación fue solicitada en 1970, pero diversos factores demoraron la producción de 33 años. En 2001 el jefe de cuerpo llegó a ella con entusiasmo para poder completar la obra a fin de conmemorar los 90 años de bomberos, no paró durante 49 días.
                        La escultura está hecha en granito reconstituido y base de mármol. Entre los detalles artísticos del monumento puede mencionarse su imponente altura: 3,15 metros. La figura central es un bombero saliendo a la acción, 
                        con los elementos para cumplir su misión.  Fábricas, casas y edificios están representados, además del sol y la vida, a través de una mujer con sus hijos.
                        </v-card-text>
                    </v-col>
                </v-row>
            </v-card>
        </v-col>
    </v-row>
</template>

<script>
    export default{
        name: 'HistoryComponent',
    }
</script>