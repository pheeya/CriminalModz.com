<template>
   <div class="infoMain">
<div class="infoTile">
<h2>{{title}}</h2>
<img width="61" height="46" v-bind:src="icon" scale="1">
<p>{{details}}
</p> 
<p id="bottomP">
{{smallDetails}}</p>

<a :href="link" target="_blank"><button><i class="fas fa-plus-circle"></i> Show More</button></a> 

</div>



   </div>

</template>

<script>
export default {
    props:['title', 'icon', 'details', 'smallDetails','link']
}
</script>

<style>
button 
{
    background-color:rgb(243, 243, 243);
    padding:10px;
    border:0;
    font-size:18px;
    font-weight:600;
    border:1px solid rgba(211, 211, 211, 0.301);
    cursor: pointer;
}
#bottomP 
{
    font-size:12px;
    
}
p 
{
color:rgb(92, 92, 92);
}
.infoTile 
{
    text-align:center;
    max-width:240px;
    padding:10px;
    box-sizing: border-box;
    background-color:white;
    margin:auto;
    height:400px;
}

.infoMain 
{
    
    padding:5px;
    display:inline-block;
    vertical-align: top;
}
</style>