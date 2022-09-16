<template>
  <n-message-provider>
    <router-view />
  </n-message-provider>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "App",
});
</script>
