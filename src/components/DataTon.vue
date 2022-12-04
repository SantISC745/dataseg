<style>
.v-sheet--offset {
    top: -40px;
    left: -40px;
    position: relative;
}
</style>
<template>
    <v-container fluid>
        <v-row>
            <v-col lg="12">
                <v-card>
                    <v-tabs v-model="tab" background-color="deep-purple accent-4" centered dark icons-and-text>
                        <v-tabs-slider></v-tabs-slider>

                        <v-tab href="#tab-1">
                            Proyecto
                            <v-icon>mdi-text-box-outline</v-icon>
                        </v-tab>

                        <v-tab href="#tab-2">
                            Métricas
                            <v-icon>mdi-ruler</v-icon>
                        </v-tab>

                        <v-tab href="#tab-3">
                            Indicadores
                            <v-icon>mdi-chart-box-outline</v-icon>
                        </v-tab>
                        <v-tab href="#tab-4">
                            Creditos
                            <v-icon>mdi-account-group-outline</v-icon>
                        </v-tab>
                    </v-tabs>

                    <v-tabs-items v-model="tab">
                        <v-tab-item value="tab-1">
                            <v-card flat>
                                <v-card-text>
                                    <p class="font-weight-black h1">
                                        INTRODUCCIÓN
                                    </p>
                                    <p class="text-justify">
                                        Un indicador se define como una función de una o más variables que,
                                        conjuntamente,
                                        miden una característica o atributo en estudio. Es una herramienta cuantitativa
                                        o
                                        cualitativa que muestra indicios o señales de una situación, actividad o
                                        resultado.

                                        En este sentido, los indicadores de corrupción se orientan a mostrar factores de
                                        riesgo en la materialización de dichos actos o comportamientos; por otra parte,
                                        la
                                        corrupción es un fenómeno que obstruye el bienestar de los países; por lo cual,
                                        como
                                        una medida para disminuirla, de acuerdo con lo señalado en el último párrafo del
                                        artículo 108 Constitucional, así como a lo indicado en la fracción XXV, del
                                        artículo
                                        3º, y artículos 32 y 46 de la Ley General de Responsabilidades Administrativas,
                                        se
                                        instauró como obligación que los servidores públicos declaren situación
                                        patrimonial
                                        e intereses.

                                        En los últimos años, esta recopilación de información se realiza a través de
                                        medios
                                        electrónicos (como la Plataforma Digital Nacional y el DECLARANET), los cuales
                                        son
                                        un pilar fundamental para la cultura de la transparencia en nuestro país; sin
                                        embargo, aún existen retos en la materia, si bien la generación de bases de
                                        datos es
                                        relevante, resulta pertinente y necesario que a partir de esa información
                                        producida
                                        mediante esta infraestructura tecnológica se formulen herramientas para
                                        identificar,
                                        prevenir y combatir la corrupción.

                                        En ese contexto, en DATASEG nos complace proponer la utilización de una
                                        herramienta
                                        basada en indicadores y métricas que relacionan los datos de los servidores
                                        públicos
                                        de las declaraciones patrimoniales y los registros de sanciones a funcionarios
                                        públicos y particulares publicados por la Plataforma Digital Nacional (
                                        https://www.plataformadigitalnacional.org/ ), a fin de proporcionar alertas de
                                        posibles riesgos de corrupción y priorizar la vigilancia en los casos críticos.

                                        Además, se presentamos el desarrollo “Audilisto”, como un medio de consulta
                                        interactivo para los usuarios interesados en conocer la información que brinda
                                        la
                                        Plataforma Digital Nacional, para contribuir a la transparencia y al uso de
                                        datos
                                        para prevenir y mitigar la corrupción en México.
                                    </p>
                                </v-card-text>
                            </v-card>
                        </v-tab-item>
                        <v-tab-item value="tab-2">
                            <v-card flat>
                                <v-card-text>
                                    <p class="font-weight-black h1">
                                        VARIACIÓN DEL INGRESO.
                                    </p>
                                    <p class="text-justify">
                                        El indicador calcula la razón de variación del ingreso total neto del servidor
                                        público en el año en estudio, respecto del año anterior. Asumiendo que puede
                                        existir
                                        un riesgo de corrupción significativo cuando dicho porcentaje muestre
                                        incrementos
                                        exponenciales, si bien pueden existir justificaciones, el indicador ayuda a
                                        focalizar la supervisión, el control e investigación en aquellos funcionarios
                                        que
                                        presenten un riesgo mayor.
                                    </p>

                                    <p class="font-weight-black">
                                        PERTINENCIA DE LA VARIACIÓN DE INGRESO, RESPECTO DE LA EXPERIENCIA LABORAL.
                                    </p>
                                    <p class="text-justify">
                                        El Indicador relaciona el resultado de la «VARIACIÓN DEL INGRESO» con la
                                        «EXPERIENCIA LABORAL DECLARADA». Asumiendo que, si existen cambios
                                        significativos en
                                        el ingreso y no se acredita experiencia para el puesto, podrían existir riesgos
                                        de
                                        corrupción, en ese sentido, se orienta a identificar los casos que pudieran ser
                                        más
                                        críticos para priorizar su vigilancia
                                    </p>
                                    <p class="font-weight-black">
                                        RAZÓN DE INGRESOS ADICIONALES.
                                    </p>
                                    <p class="text-justify">
                                        El indicador es una métrica compuesta que muestra la relación entre los ingresos
                                        netos totales y el ingreso laboral, a efecto de conocer si existe diferencia
                                        entre
                                        ambos conceptos y, en su caso, corroborar si dicha diferencia se encuentra
                                        acorde
                                        con los «otros ingresos» declarados percibidos por el funcionario público. Con
                                        este
                                        indicador se pretende identificar a aquellos servidores públicos que puedan
                                        tener
                                        ingresos netos superiores a los originalmente reportados en sus declaraciones,
                                        con
                                        la finalidad de focalizar la investigación en posibles actos de corrupción.
                                    </p>
                                    <p class="font-weight-black">
                                        FUNCIONARIO SANCIONADO.
                                    </p>
                                    <p class="text-justify">
                                        El indicador muestra sí el funcionario fue sancionado, relacionando las
                                        variables
                                        incluidas en las bases disponibles (Sistema 1. Declaración patrimonial y Sistema
                                        3.
                                        Funcionarios sancionados), a efecto de conocer sí tiene antecedentes de
                                        comportamientos contrarios a la normativa sancionados por una autoridad
                                        competente.
                                    </p>
                                </v-card-text>
                            </v-card>
                        </v-tab-item>
                        <v-tab-item value="tab-3">
                            <v-card flat>
                                <v-container fluid>
                                    <v-row>
                                        <v-col align="center" lg="12">
                                            <iframe title="Proyecto_DATASEG - Tablero_Alerta temprana"
                                                style="height: 35pc; width: 90pc"
                                                src="https://app.powerbi.com/view?r=eyJrIjoiNWM2OGRhMjQtZjk3OC00OTUzLThiMTAtNjc5ZTI4MTNlOGZlIiwidCI6IjI5NjNiZjRkLWNiNWEtNDYxMC05NGZmLWNiYTgxOTQ4YWRkMSIsImMiOjR9"
                                                frameborder="0" allowFullScreen="true"></iframe>
                                        </v-col>
                                    </v-row>
                                </v-container>
                            </v-card>
                        </v-tab-item>
                        <v-tab-item value="tab-4">
                            <v-card>
                                <v-card-text class="pa-8">
                                    <!-- <TarjetaPresentacion/> -->
                                    <v-row>
                                        <v-col v-for="(integrante, i) in integrantes" :key="i" lg="4">
                                            <v-card class="mt-2 mx-4 pa-4">
                                                <v-avatar class="v-sheet--offset" color="indigo" size="60">
                                                    <!-- <v-icon dark>
                                                mdi-account-circle
                                            </v-icon> -->
                                                    <img :src="integrante.foto" alt="John">
                                                </v-avatar>
                                                <div style="margin: 10% 0 0 40%; "></div>

                                                <v-card-text style="margin-top: -25%" class="pt-0">

                                                    <v-row>
                                                        <v-col lg="12">
                                                            <strong>Nombre: </strong>
                                                            <span>{{ integrante.nombre }}</span>
                                                        </v-col>
                                                    </v-row>
                                                    <v-row>
                                                        <v-col lg="12">
                                                            <strong>Grado: </strong>
                                                            <span>{{ integrante.grado }}</span>
                                                        </v-col>
                                                    </v-row>
                                                </v-card-text>
                                            </v-card>
                                        </v-col>
                                    </v-row>

                                </v-card-text>
                            </v-card>
                        </v-tab-item>
                    </v-tabs-items>
                </v-card>
            </v-col>
        </v-row>
    </v-container>
</template>
<script>

// import TarjetaPresentacion from './TarjetaPresentacion.vue';

export default {
    name: 'DataTon',
    // components: {
    //     TarjetaPresentacion
    // },
    data: () => ({
        urlImages: 'http://localhost:8080/public/integrantes/',
        integrantes: [
            {
                nombre: 'MARIO RAMÍREZ MEJÍA',
                grado: 'MTRO. EVALUACIÓN DE POLITICAS PÚBLICAS',
                foto: 'integrantes/mario.png'
            },
            {
                nombre: 'SANTIAGO MARTÍNEZ ZAVALA',
                grado: 'ING. SISTEMAS COMPUTACIONALES',
                foto: 'integrantes/santiago.jpeg'
            },
            {
                nombre: 'LESLY ESTEFANIA FLORES RIVERA',
                grado: 'DRA. CIENCIAS SOCIALES',
                foto: 'integrantes/lesly.jpeg'
            },
            {
                nombre: 'JESÚS MITCHELL MENDIOLA CÁRDENAS',
                grado: 'LIC. ECONOMÍA',
                foto: 'integrantes/mitchell.jpeg'
            },
            {
                nombre: 'CYNTHIA LOURDES RODRÍGUEZ MACÍAS',
                grado: 'LIC. EN ADMINISTRACIÓN PÚBLICA',
                foto: 'integrantes/cynthia.jpeg'
            },
            {
                nombre: 'DANIEL AZAÍN CERÓN AGUIRRE',
                grado: 'LIC. CIENCIAS DE LA COMUNICACIÓN',
                foto: 'integrantes/daniel.jpeg'
            },
            {
                nombre: 'FERNANDO GONZÁLEZ LOYA',
                grado: 'LIC. COMERCIO INTERNACIONAL',
                foto: 'integrantes/fernando.jpg'
            },
        ],
        tab: 'tab-1',
    })
}
</script>