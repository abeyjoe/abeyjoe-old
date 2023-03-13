<template>
<v-container>
  <hr>
  <center><h1 class="contact pa-15">CONTACT US</h1></center>


  <v-sheet width="300" class="mx-auto">
    <v-form fast-fail @submit.prevent>
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
        v-model="textFieled"
        label="Say something"
        :rules="fieldRules"
        autocomplete="off"
      ></v-text-field>

      <v-btn type="submit" block class="mt-2">Submit</v-btn>
    </v-form>
  </v-sheet>

<br><br>




































<!--
  <v-timeline>
    <v-timeline-item
      dot-color="purple-lighten-2"
      fill-dot
    >
      <v-card>
        <v-card-title class="bg-purple-lighten-2">
          <v-icon
            size="large"
            class="me-4"
            icon="mdi-magnify"
          ></v-icon>
          <h2 class="font-weight-light">
            Title 1
          </h2>
        </v-card-title>
        <v-card-text>
          Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit.
        </v-card-text>
      </v-card>
    </v-timeline-item>

    <v-timeline-item
      dot-color="amber-lighten-1"
      fill-dot
      size="x-small"
    >
      <v-card>
        <v-card-title class="bg-amber-lighten-1 justify-end">
          <h2 class="me-4 font-weight-light">
            Title 2
          </h2>
          <v-icon
            size="large"
            icon="mdi-home-outline"
          ></v-icon>
        </v-card-title>
        <v-card-text>
          Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit.
        </v-card-text>
      </v-card>
    </v-timeline-item>

    <v-timeline-item
      dot-color="cyan-lighten-1"
      fill-dot
    >
      <v-card>
        <v-card-title class="bg-cyan-lighten-1">
          <v-icon
            class="me-4"
            size="large"
            icon="mdi-email-outline"
          ></v-icon>
          <h2 class="font-weight-light">
            Title 3
          </h2>
        </v-card-title>
        <v-card-text>
          Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit.
        </v-card-text>
      </v-card>
    </v-timeline-item>

    <v-timeline-item
      dot-color="red-lighten-1"
      fill-dot
      size="x-small"
    >
      <v-card>
        <v-card-title class="bg-red-lighten-1 justify-end">
          <h2 class="me-4 font-weight-light">
            Title 4
          </h2>
          <v-icon
            size="large"
            icon="mdi-account-multiple-outline"
          ></v-icon>
        </v-card-title>
        <v-card-text>
          Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit.
        </v-card-text>
      </v-card>
    </v-timeline-item>

    <v-timeline-item
      dot-color="green-lighten-1"
      fill-dot
    >
      <v-card>
        <v-card-title class="bg-green-lighten-1">
          <v-icon
            class="me-4"
            size="large"
            icon="mdi-phone-in-talk"
          ></v-icon>
          <h2 class="font-weight-light">
            Title 5
          </h2>
        </v-card-title>
        <v-card-text>
          Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit.
        </v-card-text>
      </v-card>
    </v-timeline-item>
  </v-timeline>
-->
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
      fieldRules: [
        value => {
          if (value?.length > 3) return true

          return 'Text field must be at least 3 characters.'
        },
      ],

    }),
  }
</script>
