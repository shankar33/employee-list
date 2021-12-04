<script>
import { defineComponent } from 'vue';
import ChildComponent from './ChildComponent.vue'

export default /*#__PURE__*/defineComponent({
  name: 'EmployeeListSample', // vue component name
  props: {
    theName: String
  },
  components: {
    ChildComponent
  }
});
</script>
<template>
  <div>
    <h1>Hi {{theName}},</h1>
    <h3>This is from parent component.</h3>
    <ChildComponent />
  </div>
</template>
