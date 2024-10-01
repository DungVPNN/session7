<script setup>
import ChildrenComponet from './ChildrenComponet.vue'
const userName='NGUYEN VAN A'
const age=18

const arr = {
    id:1,
    name:'DUNG',
    age:19
}
</script>

<template>
  <div>Cha
    <h3>{{userName}}</h3>
    <p>---------------------</p>
    <ChildrenComponet :arr1='arr'></ChildrenComponet>
  </div>
</template>

<style>

</style>