<template>
    <ul>
        <li v-for="(section, index) in sections" :key="index"> <a href="#">{{ section }}</a> </li>
    </ul>
</template>

<script>
export default {
    name: "NavBar",
    data(){
        return {
        sections: ['Circulação', 'Circulação', 'Circulação', 'Dashboard']
        }
     }
}
</script>

<style scoped>
ul {
    list-style: none;
    display: flex;
    text-align: center;
    padding: 10px 10px;
}

li{
    padding: 5px 10px;
    margin-left: auto;
    margin-right: auto;

}
</style>