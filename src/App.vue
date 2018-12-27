<template name='App'>
  <div class="app">
    <div class="main">
      <router-view/>
    </div>
    <navbar></navbar>
  </div>
</template>

<script>
import navbar from "@/components/Public/navbar";
export default {
  name: "App",
  components: { navbar }
};
</script>