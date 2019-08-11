<template>
<div class="main">
    <div class="container">
<div class="tile left">

<h1>GTA Online Modded Services</h1>
<p>CriminalModz is a Trusted & Reliable GTA Online Mods Provider. 
We offer modifications such as GTA V Money, Level, Unlocks, Bundles, etc. for PC, PS4 & Xbox One! Enjoy Full Money-Back Guarantee, Anti-Ban Warranty & Anti-Modder Protection</p>
<button>Support</button> <button id='reviews'>View Reviews</button>

</div>
<div id="gangTile" class="tile">
<img id="gangMember" width="336" height="477" src="https://i0.wp.com/criminalmodz.com/wp-content/uploads/2019/08/368-3682345_grand-theft-auto-v-png-hd-gta-5.png?fit=336%2C477&amp;ssl=1" class="attachment-full size-full jetpack-lazy-image jetpack-lazy-image--handled" alt="" srcset="https://i0.wp.com/criminalmodz.com/wp-content/uploads/2019/08/368-3682345_grand-theft-auto-v-png-hd-gta-5.png?w=336&amp;ssl=1 336w, https://i0.wp.com/criminalmodz.com/wp-content/uploads/2019/08/368-3682345_grand-theft-auto-v-png-hd-gta-5.png?resize=211%2C300&amp;ssl=1 211w" data-lazy-loaded="1" sizes="(max-width: 336px) 100vw, 336px">
</div>

    </div>
    
    
</div>    


</template>


<script>
export default {
    
}
</script>
<style scoped>
.main 
{
  
}
.left 
{
    background-color:white;
    padding:0 15px;
    max-height:300px;
}
@media (min-width:2000px){
    .left{
        margin-top:4vw;
    }
}
.tile 
{
     box-sizing: border-box;
 max-width:550px;
 border-radius:8px;
 font-size:18px;
   
}
#gangTile 
{
   
    padding-right:0;
    text-align:Center;
    margin:auto;

}

#gangMember 
{
     width:13vw;
    filter: brightness( 100% ) contrast( 100% ) saturate( 100% ) blur( 0px ) hue-rotate( 0deg );
    box-shadow: 0px 0px 10px 0px rgba(0,0,0,0);
        vertical-align: top;
    display: inline-block;
    height: auto;
    max-width: 100%;
    border: none;
    text-align: center;
         
}
button 
{
   padding:13px 18px;
    border-radius:5px;
    border:0;
    background-color:rgb(221, 3, 3);
    font-size:15px;
    font-weight:600;
    color:rgb(255, 255, 255);
    margin:15px 0;
    transition:all .4s;
    cursor: pointer;
}
#reviews 
{
    background-color:white;
    color:rgb(37, 37, 37);
    box-shadow:2px 2px 1px rgba(71, 71, 71, 0.185);
    margin-left:10px;
}
button:hover, #reviews:hover 
{
    color:white;
    background-color:rgb(51, 51, 51);
}



.main 
{  
    padding:0;
    max-height:550px;
    max-width:1200px;
    margin:auto;
        padding:25px;
color:rgb(0, 0, 0);
     box-sizing: border-box;
}

h1 
{
    margin:15px 0;
    line-height:1.5;
    font-size:33px;
    font-weight:600;
}
.container 
{
     display:flex;
         box-sizing: border-box;
         
}
p 
{
    font-size:16px;
    line-height:1.5;
    color:rgb(99, 99, 99);
}

@media (max-width: 800px){
    #gangTile{
        display:none;
    }
    .tile 
    {
        text-align:center;
    }
    .main 
    {
        padding:0;
    }
}
</style>
