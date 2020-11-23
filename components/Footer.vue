<template>
  <v-footer :absolute="!fixed" app>
    <v-container>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-container>
  </v-footer>
</template>