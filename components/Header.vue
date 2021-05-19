<template>
<div>
    <div id="header">
        <Logo />
        <ul>
            <li><a href="#">Quem somos</a></li>
            <li><a href="#">Lista de Verificação</a></li>
            <li><a href="#">Solicite um orçamento</a></li>
            <li><a href="#">Contato</a></li>
        </ul>
    </div>
</div>
    

    
</template>

<script>
export default {
    name: "Header",
    
}
</script>

<style scoped>
#header {
    display: flex;
    align-items: center;
}

ul {
    list-style: none;
    display: flex;
    float: right;
    position: absolute;
    right: 0;
    top: 2px;

}

li{
    padding: 5px 10px;
    border-top: 0;
    right: 10px;
}

#searchbar{
  padding: 6px;
  margin-top: 8px;
  font-size: 17px;
  display: flex;
  position: absolute;
  right: 0;
  top: 60px;
    
}
</style>