<template>

  {{ name }}
  { othername }
  <CommonHeader ></CommonHeader>

</template>


<script setup>
import { ref, onMounted } from 'vue';

const name = 'dipesh'
const othername = ref('basnet')
const addName = () => {
  othername.value = 'newvalue'
  console.log('dd')
}

watch(name, () => {

})
const complexVarible = computed(() => {
  return name + othername
})


onMounted(() => {
  addName()
  othername.value = 'karen'

})

</script>


<style scoped></style>
