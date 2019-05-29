<template>
  <div class="container-fluid">
    <div class="row">
      <leftside />
      <rightside />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import leftside from "@/components/leftmenu.vue";
import rightside from "@/components/rightscreen.vue";

export default {
  name: "home",
  components: {
    leftside,
    rightside,
  }
};
</script>
