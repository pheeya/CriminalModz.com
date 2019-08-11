<template>
    <div class="cardMain">
<h4><span><img width="500" height="500" :src='imgLink'></span>{{title}}</h4>
<p>{{content}}</p>
    </div>
</template>

<script>
export default {
    props:['title', 'imgLink','content']
}
</script>


<style lang="scss" scoped>
img 
{
    width:50px;
    height:auto;
    vertical-align:middle;
    margin-right:10px;
}
.cardMain 
{
    text-align: left;
    max-width:350px;
  background-color:white;
  margin:15px;
  border-radius:8px;
}
h4 
{
    font-weight:600;
    font-family:sans-serif;
    margin-bottom:0;
}
p 
{
    margin-top:0;
    margin-left:60px;
}

</style>