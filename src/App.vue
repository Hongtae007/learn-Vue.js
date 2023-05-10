<script>
export default {
  name : 'App',
  data(){
    return{
      firstName:"ธีระพงศ์",
      lastName:"สายอ๋อง",
      age:20,
      count: 0,
      address:"<strong>สงขลา</strong>"
    }
  },
}

</script>

<template>
<section>
  <h1>theerapong</h1>
    <h1>ชื่อ : {{ firstName }}</h1>
    <h1>สกุล : {{ lastName }}</h1>
    <h1>อายุ : {{ age }}</h1>
    <p>ที่อยู่ : <span v-html="address"></span></p>
  <div id="app">
    <button @click="count++">
    Count is: {{ count }}
    </button>
  </div>
  </section>
  
</template>

<style>

</style>
