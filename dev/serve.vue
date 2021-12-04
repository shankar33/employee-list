<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'ServeDev',
  data() {
    return {
      msg: "World"
    }
  }
});
</script>
<template>
  <div id="app">
    <employee-list-sample :theName="msg" />
  </div>
</template>
