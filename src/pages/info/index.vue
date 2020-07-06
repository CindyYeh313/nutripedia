<script>
import fruit from '../../assets/fruit.json'
export default {
    data(){
        return {
            fruit,
            currentIdx: 0
        }
    },
    methods:{
        itemChange(idx){
            console.log(idx)
            this.currentIdx = idx
        }
    }
}
</script>

<template src="./template.html" />
<style lang="scss" src="./style.scss" />