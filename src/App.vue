<template>
  <v-app>
    <v-main>
      <GoogledarkUI />
    </v-main>
  </v-app>
</template>

<script setup>
import GoogledarkUI from "@/components/Google_dark.vue";
import { onMounted } from "vue";
import { useTheme } from "vuetify";

const theme = useTheme();

function toggleTheme() {
  theme.global.name.value = theme.global.current.value.dark ? "light" : "dark";
}

onMounted(() => {
  toggleTheme();
});
</script>
