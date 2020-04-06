<template>
  <div>
    <Checkbox
      v-model="checkboxValue"
      name="Your custom name"
      text="Your custom text"
    />
  </div>
</template>

<script>
import Checkbox from "./checkbox.vue";

export default {
  components: { Checkbox },
  data() {
    return {
      checkboxValue: false //bind with v-model
    };
  }
};
</script>



