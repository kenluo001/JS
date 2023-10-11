<!--
 * @Author: Ken Luo ken.luo.5227@gmail.com
 * @Date: 2023-10-11 15:41:33
 * @FilePath: /JS/vue/hello.vue
-->
<!--
跟 Vue 说 Hello World！
-->

<script setup>
import { ref } from 'vue'

// “ref”是用来存储值的响应式数据源。
// 理论上我们在展示该字符串的时候不需要将其包装在 ref() 中，
// 但是在下一个示例中更改这个值的时候，我们就需要它了。
const message = ref('Hello World!')
</script>

<template>
  <h1>{{ message }}</h1>
</template>