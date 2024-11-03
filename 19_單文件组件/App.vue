<template>
  <!-- 母版裡面必須要有一個根元素 -->
  <div>
    <School></School>
    <Student></Student>
  </div>
</template>

<script>
//引入组件
import School from "./School.vue";
import Student from "./Student.vue";

export default {
  name: "App",
  components: {
    School,
    Student,
  },
};
</script>
