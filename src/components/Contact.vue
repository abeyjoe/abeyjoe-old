<template>
<v-container>
  <hr>
  <center><h1 class="contact pa-15">CONTACT US</h1></center>


  <v-sheet width="300" class="mx-auto">
    <v-form fast-fail> <!--@submit.prevent-->
      <v-text-field
        v-model="firstName"
        label="First name"
        :rules="firstNameRules"
        autocomplete="off"
      ></v-text-field>

      <v-text-field
        v-model="email"
        :rules="emailRules"
        label="E-mail"
        required
        autocomplete="off"
      ></v-text-field>

      <v-text-field
        v-model="textField"
        label="Description"
        :rules="fieldRules"
        required
        autocomplete="off"
      ></v-text-field>
     
      <v-btn type="submit" block class="mt-2">Submit</v-btn>
    </v-form>
  </v-sheet>

<br><br>


</v-container>
</template>

<script>
  export default {
    data: () => ({
      firstName: '',
      firstNameRules: [
        value => {
          if (value?.length > 3) return true

          return 'First name must be at least 3 characters.'
        },
      ],
      email: '',
      emailRules: [
        value => {
          if (value) return true

          return 'E-mail is requred.'
        },
        value => {
          if (/.+@.+\..+/.test(value)) return true

          return 'E-mail must be valid.'
        },
      ],
      textField: '',
      fieldRules: [
        value => {
          if (value?.length > 3) return true

          return 'Text field must be at least 3 characters.'
        },
      ],

    }),
  }
</script>
