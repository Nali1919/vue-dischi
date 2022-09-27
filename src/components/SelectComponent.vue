<template>
  <div>
    <select name="" id="" v-model="genere" @change="cambioGenere">
        <option value="All">All</option>
        <option value="Jazz">Jazz</option>
        <option value="Metal">Metal</option>
        <option value="Pop">Pop</option>
        <option value="Rock">Rock</option>
    </select>
  </div>
</template>

<script>
export default {
    data() {
        return {
            genere: ''
        }
    },
    methods: {
        cambioGenere() {
     console.log(this.genere)
    }
},
name: 'SelectComponent'
}

</script>

<style>

</style>