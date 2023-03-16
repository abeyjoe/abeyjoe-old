<template>
<center>

    <div class="about">
        <h1 class="pa-15 subheading gray--text">ABOUT</h1>

        <v-container>
            <v-row cols="12">
                <v-col col xs="12" sm="6" md="3" lg="3">
                    <v-sheet class="rounded pa-5" height="300" width="280">
                        <v-icon style="height:2em;" icon="mdi-speedometer"></v-icon>
                        <h2>Fast</h2>
                        <p>With VueJS, fast load times and lag free interaction, my highest priority.</p>
                    </v-sheet>
                </v-col>
                <v-col col xs="12" sm="6" md="3" lg="3">
                    <v-sheet class="rounded pa-5" height="300" width="280">
                        <v-icon icon="mdi-cellphone-link"></v-icon>
                        <h2>Responsive</h2>
                        <p>My layouts will work on any device, big or small.</p>
                    </v-sheet>
                </v-col>
                <v-col col xs="12" sm="6" md="3" lg="3">
                    <v-sheet class="rounded pa-5" height="300" width="280">
                        <v-icon icon="mdi-lightbulb-outline"></v-icon>
                        <h2>Intuitive</h2>
                        <p>Strong preference for easy to use, intuitive UX/UI.</p>
                    </v-sheet>
                </v-col>
                <v-col col xs="12" sm="6" md="3" lg="3">
                    <v-sheet class="rounded pa-5" height="300" width="280">
                        <v-icon icon="mdi-rocket"></v-icon>
                        <h2>Dynamic</h2>
                        <p>Websites don't have to be static, I love making pages come to life.</p>
                    </v-sheet>
                </v-col>
            </v-row>
        </v-container>


        <v-container></v-container>

        
        <!-- ABOUT THE AUTHOR -->
        <v-container>
            <v-row cols="12">
                <v-col col xs="12" sm="12" md="12" lg="6">
                    <v-sheet class="rounded pa-5" height="450" width="450">
                        <!-- <v-icon icon="mdi-group"></v-icon> -->
                        <!-- <h2>IMAGE HERE</h2> -->
                        <img src="../assets/ceo.jpg" alt="Abiodun Adedapo CEO PKA Abeyjoe" style="width:250px; height:300px;border-radius:10px;" />
                        <v-card-subtitle>I am Abiodun Adedapo</v-card-subtitle>
                        <p class="ceo">I'm a Fullstack Developer for Abeyjoe in Lagos, Nigeria. An experienced professional with serious passion 
                            for UI effects, animations, web application, APIs and creating intuitive, and dynamic user experiences. <br>
                            A specialist in developing Web Application APIs with the use of VueJS. <a href="#">Let's make something special.</a></p>
                    </v-sheet>
                </v-col>
                <v-col col xs="12" sm="12" md="12" lg="3">
                    <v-sheet class="rounded" height="450" width="450">
                        <v-icon icon="mdi-cellphone-link"></v-icon>
                        <h2>Profile Skills</h2>
                        <!-- <ul class="">
                            <li>Git</li>
                            <li>Wireframing</li>
                            <li>DNS Management</li>
                            <li>Testing, Debugging</li>
                            <li>Fron-end frameworks</li>
                            <li>Responsive design</li>
                            <li>User experience</li> UI/UX
                            <li>User interface</li> UI/UX
                            <li>CMS with WordPress</li>
                            <li>Document object model</li>
                            <li>APIs</li>
                            <li>Search Engine Optimization (SEO)</li>

    color="light-blue"
    color="deep-orange"
    color="light-green-darken-4"
    color="lime"
    color="deep-orange"

                        </ul> -->
                            <v-container>
                                <div>
                                  <p class="skill">HTML, CSS &amp Bootstrap</p>
                                  <v-progress-linear
                                    model-value="96"
                                    height="10"
                                    striped
                                    color="deep-orange"
                                  ><b>96%</b></v-progress-linear>

                                  <p class="skill">Vue JS</p>
                                  <v-progress-linear
                                    model-value="75"
                                    color="deep-orange"
                                    height="10"
                                    striped
                                  >75%</v-progress-linear>

                                  <p class="skill">NodeJS</p>
                                  <v-progress-linear
                                    model-value="35"
                                    height="10"
                                    striped
                                    color="deep-orange"
                                  ><b>35%</b></v-progress-linear>

                                  <p class="skill">PHP</p>
                                  <v-progress-linear
                                    model-value="75"
                                    height="10"
                                    striped
                                    color="deep-orange"
                                  ><b>75%</b></v-progress-linear>

                                  <p class="skill">MySQL</p>
                                  <v-progress-linear
                                    model-value="86"
                                    height="10"
                                    striped
                                    color="deep-orange"
                                  ><b>86%</b></v-progress-linear>

                                  <p class="skill">WordPress</p>
                                  <v-progress-linear
                                    model-value="90"
                                    height="10"
                                    striped
                                    color="deep-orange"
                                  ><b>90%</b></v-progress-linear>
                                  
                                  <p class="skill">Testing &amp; Debugging</p>
                                  <v-progress-linear
                                    model-value="89"
                                    color="deep-orange"
                                    height="10"
                                    striped
                                  >89%</v-progress-linear>
                                </div>
                            </v-container>
                    </v-sheet>
                </v-col>
            </v-row>
        </v-container>

    </div>
</center>
</template>

<script>
export default {

}
</script>

<style scoped>
.rounded:hover {
    opacity: 90%;
}
p.ceo {
    font-size: 10px;
    padding-left:20px;
    padding-right:20px;
    /* padding-bottom:20px; */
}
p.skill {
    padding-top: 15px;
}
</style>
