<template>
  <hr>

  <v-footer class="d-flex flex-column">
    <div class="bg-dark d-flex w-100 align-center px-4">
      <!-- <strong>Get connected with us on social networks!</strong> -->


      <v-spacer></v-spacer>


      <v-btn
        icon="mdi-facebook"
        href="https://web.facebook.com/abiodun.adedapo.127/"
        target="_blanck"
        class="mx-4"
        variant="plain"
        size="small"
      ></v-btn>

<!--
      <v-btn
        icon="mdi-phone"
        href="09024056004"
        target="_blanck"
        class="mx-4"
        variant="plain"
        size="small"
      ></v-btn>
-->

      <v-btn
        icon="mdi-whatsapp"
        href="https://wa.me/message/2C5OUURRHLHEF1"
        target="_blanck"
        class="mx-4"
        variant="plain"
        size="small"
      ></v-btn> 
      <v-btn
        icon="mdi-instagram"
        href="https://www.instagram.com/adedapo_abiodun/"
        target="_blanck"
        class="mx-4"
        variant="plain"
        size="small"
      ></v-btn> 
      <v-btn
        icon="mdi-twitter"
        href="https://twitter.com/AbeyjoeAbiodun"
        target="_blanck"
        class="mx-4"
        variant="plain"
        size="small"
      ></v-btn> 

<!--
      <v-btn
        icon="mdi-linkedin"
        href=""
        target="_blanck"
        class="mx-4"
        variant="plain"
        size="small"
      ></v-btn> 
-->

<!--
      <v-btn
        v-for="icon in icons"
        :key="icon"
        class="mx-4"
        :icon="icon"
        :href="href"
        variant="plain"
        size="small"
      ></v-btn> 
-->
    </div>

    <div class="px-4 py-2 bg-dark text-center w-100">
      <p>&copy; Copyright {{ new Date().getFullYear() }} — <strong>Abeyjoe</strong></p>
    </div>
  </v-footer>

</template>

<style scoped>
v-btn {
align:center;
}
</style>
