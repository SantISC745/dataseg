<style>
.v-sheet--offset {
    top: -40px;
    left: -40px;
    position: relative;
}
</style>
<template>
    <v-card class="mt-10 mx-8 pa-4" max-width="400">
        <v-avatar class="v-sheet--offset" color="indigo" size="50">
            <v-icon dark>
                mdi-account-circle
            </v-icon>
        </v-avatar>
        <div style="margin: 10% 0 0 40%; "></div>
        <!-- <v-sheet class="v-sheet--offset" color="red" elevation="6" width="40%" height="100px" align="center">
            <v-icon style="color: white; font-size: 45px; padding: 15%; margin-top: 4%;">mdi-gift</v-icon>
        </v-sheet> -->

        <v-card-text style="margin-top: -25%" class="pt-0">
            <!-- <table>
                <thead>
                </thead>
                <tbody style="text-align: center;">
                    <tr>
                        <th></th>
                        <th>Pendiente</th>
                        <th>Reservado</th>
                        <th>Otorgado</th>
                    </tr>

                </tbody>
            </table> -->
            <v-row>
                <v-col lg="12">
                    <strong>Nombre: </strong>
                    <span>{{integrante.nombre}}</span>
                </v-col>
            </v-row>
            <v-row>
                <v-col lg="12">
                    <strong>Grado: </strong>
                    <span>{{integrante.grado}}</span>
                </v-col>
            </v-row>
        </v-card-text>
    </v-card>
</template>
<script>
export default {
    name: 'TarjetaPresentacion',
    data: () => ({
        integrantes: [
            {
                nombre: 'MARIO RAMÍREZ MEJÍA',
                grado: 'MTRO. EVALUACIÓN DE POLITICAS PÚBLICAS'
            },
            {
                nombre: 'SANTIAGO MARTÍNEZ ZAVALA',
                grado: 'ING. SISTEMAS COMPUTACIONALES'
            },
            {
                nombre: 'LESLY ESTEFANIA FLORES RIVERA',
                grado: 'DRA. CIENCIAS SOCIALES'
            },
            {
                nombre: 'JESÚS MITCHELL MENDIOLA CÁRDENAS',
                grado: 'LIC. ECONOMÍA'
            },
            {
                nombre: 'CYNTHIA LOURDES RODRÍGUEZ MACÍAS',
                grado: 'LIC. EN ADMINISTRACIÓN PÚBLICA'
            },
            {
                nombre: 'DANIEL AZAÍN CERÓN AGUIRRE',
                grado: 'LIC. CIENCIAS DE LA COMUNICACIÓN'
            },
            {
                nombre: 'FERNANDO GONZÁLEZ LOYA',
                grado: 'LIC. COMERCIO INTERNACIONAL'
            },
        ]
    })
}
</script>