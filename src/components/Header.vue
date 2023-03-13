<template>
<v-toolbar color="light" :sticky="sticky" lines="one">

    <template v-slot:prepend>
    <div class="text-h5">Abeyjoe</div>
    </template>

    <v-divider
    class="ms-3"
    inset
    vertical
    ></v-divider>

    <v-toolbar-title>My Portfolio</v-toolbar-title>

    <v-spacer></v-spacer>

    <!-- <v-divider vertical></v-divider> -->

    <v-icon icon="mdi-theme-light-dark" @click="toggleTheme" style="padding:30px;"></v-icon>
                        
    <!-- <v-app-bar-nav-icon class="ms-2" @click="toggleTheme"></v-app-bar-nav-icon> -->

</v-toolbar>
</template>

<script>
import { useTheme } from 'vuetify'

export default {
  setup () {
    const theme = useTheme()

    return {
      theme,
      toggleTheme: () => theme.global.name.value = theme.global.current.value.dark ? 'light' : 'dark'
    }
  }
}
</script>
