<template>
  <div class="project">
  <center><h1 class="pa-15 subheading gray--text m-auto">PROJECT</h1></center>

<v-row>
<!--== PROJECT ITEM 1 ==-->
<div class="project-item">

<v-card
    class="mx-auto"
    max-width="344"
  >
    <v-img
      src="../assets/bosun.png"
      height="200px"
      cover
    ></v-img>

    <v-card-title>
      Bosun-Crown Electrical Contractor
    </v-card-title>

    <v-card-subtitle>
      HTML, CSS, Bootstrap and JavaScript
    </v-card-subtitle>

    
    <v-card-actions>
      <a href="https://www.bosuncrown.com" target="_blanck">
      <v-btn
        color="orange-lighten-2"
        variant="text"
      >
        Explore
      </v-btn>
    </a>

      <v-spacer></v-spacer>

      <v-btn
        :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'"
        @click="show = !show"
      ></v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show">
        <v-divider></v-divider>

        <v-card-text>
          Bosun-Crown Electrical Contractor is a certified professional in all kinds of electrical installation and maintainance of various home appliances. <br>
          This project was developed with HTML, CSS &amp; Bootstrap. &copy; 2023 <br>
          <code>Developed By: <span>Abeyjoe</span></code>
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>


</div>

<!--== PROJECT ITEM 2 ==-->
<div class="project-item">

<v-card
        class="mx-auto"
        max-width="344"
      >
        <v-img
          src="../assets/calculator.png"
          alt="JavaScript Calculator"
          height="200px"
          cover
        ></v-img>
    
        <v-card-title>
          Basic JavaScript Calculator
        </v-card-title>
    
        <v-card-subtitle>
          HTML, CSS and JavaScript
        </v-card-subtitle>
    
        <v-card-actions>
          <a href="https://calculatorlive.netlify.app" target="_blanck">
          <v-btn
            color="orange-lighten-2"
            variant="text"
          >
            Explore
          </v-btn>
        </a>
    
          <v-spacer></v-spacer>
      
          <v-btn
            :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'"
            @click="show1 = !show1"
          ></v-btn>

        </v-card-actions>
    
        <v-expand-transition>
          <div v-show="show1">
            <v-divider></v-divider>
    
            <v-card-text>
              This online calculator was my second SIWESS project at Originatorstech 
              back then in september, 2020.
              This basic javascript calculator made with HTML, CSS and JavaScript Only.<br>
              <code>Developed By:<span>Abeyjoe</span></code>
            </v-card-text>
          </div>
        </v-expand-transition>
      </v-card>
  

</div>

<!--== PROJECT ITEM 3 ==-->
<div class="project-item">

<v-card
    class="mx-auto"
    max-width="344"
  >
    <v-img
      src="../assets/weather.png"
      height="200px"
      cover
    ></v-img>

    <v-card-title>
      Weather Forcasting Web App
    </v-card-title>

    <v-card-subtitle>
      Vue JS web app
    </v-card-subtitle>

    <v-card-actions>
      <a href="https://abeyjoe-weather.netlify.app" target="_blanck">
          <v-btn
            color="orange-lighten-2"
            variant="text"
          >
            Explore
          </v-btn>
        </a>
        
      <v-spacer></v-spacer>

      <v-btn
        :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'"
        @click="show2 = !show2"
      ></v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show2">
        <v-divider></v-divider>

        <v-card-text>
          Weather forcasting system is made with web app capable of detecting the exact temperature degree of any location (state or country) aound the globe in degree celcious. <br>
          This project was developer with vue javascript. <br>
          <code>Developed By:<span>Abeyjoe</span></code>
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>

</div>

<!--== PROJECT ITEM 4 ==-->
<div class="project-item">

<v-card
    class="mx-auto"
    max-width="344"
  >
    <v-img
      src="../assets/todo.png"
      height="200px"
      cover
    ></v-img>

    <v-card-title>
      TODO LIST APPLICATION
    </v-card-title>

    <v-card-subtitle>
      VueJS, NodeJS, HTML &amp; CSS.
    </v-card-subtitle>

    <v-card-actions>
    <a href="https://abeyjoe-todo.netlify.app/" target="_blanck">
      <v-btn
        color="orange-lighten-2"
        variant="text"
      >
        Explore
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn
        :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'"
        @click="show3 = !show3"
      ></v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show3">
        <v-divider></v-divider>

        <v-card-text>
          Todo list application suitable for daily uses &amp; activities. With is web application, users can note down plans for the day either personal or business. The system is configured to enable user to create TODOs, Edit TODOs, Delete TODOs, &amp; Successfully tick completed task. Some benefits this web app provides are Local storage medium and can store unlimited TODOs for a whole year or more. <br>
          This project was developed with vue javascript.
          <code>Developed By:<span>Abeyjoe</span></code>
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>

</div>

<!--== PROJECT ITEM 5 ==-->
<div class="project-item">

<v-card
    class="mx-auto"
    max-width="344"
  >
    <v-img
      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
      height="200px"
      cover
    ></v-img>

    <v-card-title>
      Coming soon...
    </v-card-title>

    <v-card-subtitle>
      Watchout...
    </v-card-subtitle>

    <v-card-actions>
      <v-btn
        color="orange-lighten-2"
        variant="text"
      >
        Explore
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn
        :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'"
        @click="show4 = !show4"
      ></v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show4">
        <v-divider></v-divider>

        <v-card-text>
          I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>

</div>

<!--== PROJECT ITEM 6 ==-->
<div class="project-item">

<v-card
    class="mx-auto"
    max-width="344"
  >
    <v-img
      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
      height="200px"
      cover
    ></v-img>

    <v-card-title>
      Coming soon...
    </v-card-title>

    <v-card-subtitle>
      Watchout...
    </v-card-subtitle>

    <v-card-actions>
      <v-btn
        color="orange-lighten-2"
        variant="text"
      >
        Explore
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn
        :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'"
        @click="show5 = !show5"
      ></v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show5">
        <v-divider></v-divider>

        <v-card-text>
          I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>

</div>

</v-row>


  </div>

</template>

<script>
  export default {
    data: () => ({
      show: false,
      show1: false,
      show2: false,
      show3: false,
      show4: false,
      show5: false,
      show6: false,
    }),
  }
</script>

<style scoped>
.v-card--reveal {
  bottom: 0;
  opacity: 1 !important;
  position: absolute;
  width: 100%;
}
span {
  color: orange;
}
div.project {
    padding:20px;
}
.project-item {
    width:300px;
    height:auto;
    margin: 15px auto;
}
</style>
