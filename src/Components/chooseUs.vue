<template>
    <div class="main">
        <div class="opener">
<h1>Why People <span>Choose Us</span></h1>
<p>If you are looking for a trusted and safe Grand Theft
     Auto Online site CriminalModz is the right place for you!</p>
</div>
     <div class="sections">
<div class="section leftSection">
<cmp-left></cmp-left>

</div>

<div class="sectin rightSection">

<cmp-right></cmp-right>
</div>
</div>
<cmp-pay></cmp-pay>
    </div>
</template>

<script>
import leftSection from "./subComponents/leftSection"
import rightSection from "./subComponents/rightSection"
import payments from "./payments"
export default {
    components:{
        cmpLeft:leftSection,
        cmpRight:rightSection ,
        cmpPay:payments 
    }
}
</script>

<style lang="scss" scoped>
.opener 
{
    background-color:white;
    padding:20px;
}
.main 
{
 
    box-sizing: border-box;
    display:grid;
    padding:20px;
    font-family: 'Montserrat', sans-serif;
    text-align:center;
}
.sections
{
    display:grid;
    grid-template-columns: 60% 40%;
    max-width:1200px;
    margin:auto;
}
h1 
{
    span{
        color:rgb(207, 6, 6);
    }
}
p 
{
    font-weight:600;
    font-size:14px;
    color:rgba(31, 31, 31, 0.637);
   
}
</style>