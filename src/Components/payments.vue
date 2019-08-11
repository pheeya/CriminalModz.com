<template>
    <div class="main">
<ul>
    <li>
        <div class="cont">
            <div class="image">
            <img width="131" height="87" src="https://criminalmodz.com/wp-content/uploads/2018/11/mastercard.svg" class="attachment-full size-full jetpack-lazy-image jetpack-lazy-image--handled" alt="Pay with Mastercard" data-lazy-loaded="1" scale="0">
            </div>
            <div class="fee">
            Fee:0.00%
            </div>
        </div>
    </li>


    <li><div class="cont">
            <div class="image visa">
           <img width="1" height="1" src="https://criminalmodz.com/wp-content/uploads/2019/04/visa.svg" class="attachment-large size-large jetpack-lazy-image jetpack-lazy-image--handled" alt="pay by visa" data-lazy-loaded="1" scale="0">
            </div>
            <div class="fee visa">
            Fee:0.00%
            </div>
        </div></li>



    <li><div class="cont">
            <div class="image express">
            <img src="https://i1.wp.com/criminalmodz.com/wp-content/uploads/2018/11/1024px-American_Express_logo_2018.svg.png?w=1024&ssl=1">
            </div>
            <div class="fee express">
            Fee:0.00%
            </div>
        </div></li>



    <li><div class="cont">
            <div class="image deal">
            <img src="https://i2.wp.com/criminalmodz.com/wp-content/uploads/2019/04/ideal-logo-png-transparent.png?resize=1024%2C919&ssl=1">
            </div>
            <div class="fee deal">
            Fee:0.00%
            </div>
        </div></li>



    <li><div class="cont">
            <div class="image giro">
            <img src="https://criminalmodz.com/wp-content/uploads/2019/04/Giropay.svg">
            </div>
            <div class="fee giro">
            Fee:0.00%
            </div>
        </div></li>



    <li><div class="cont">
            <div class="image klarna">
            <img src="https://criminalmodz.com/wp-content/uploads/2018/11/klarna.svg">
            </div>
            <div class="fee klarna">
            Fee:0.00%
            </div>
        </div></li>



    <li><div class="cont">
            <div class="image amazon">
            <img id='amazon' src="https://i1.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Amazon-Pay-logo-1024x197.png?fit=1024%2C197&amp;ssl=1" class="attachment-full size-full jetpack-lazy-image jetpack-lazy-image--handled" alt="pay with Amazon pay" srcset="https://i1.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Amazon-Pay-logo-1024x197.png?resize=1024%2C197&amp;ssl=1 1024w, https://i1.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Amazon-Pay-logo-1024x197.png?resize=300%2C58&amp;ssl=1 300w, https://i1.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Amazon-Pay-logo-1024x197.png?resize=768%2C148&amp;ssl=1">
            </div>
            <div class="fee amazon">
            Fee:0.00%
            </div>
        </div></li>

</ul>

    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

.visa 
{
    margin-top:14px;
}
.giro 
{
    margin-top:6px;
}

.klarna 
{
    margin-top:2px;
}

.amazon img 
{
    width:100px;
}

.main 
{
    text-align:left;
    ul 
    {
        text-align:center;
       
        list-style-type:none;
        li 
        {
            display:inline-block;
            margin:20px;
        }
    }
}
#amazon 
{

}
.cont 
{
  
}
.image{
   text-align:center;
      

vertical-align: middle;
width:120px;
    
    img {
         vertical-align:middle;
         height:auto;
         width:80px;
        padding:10px;
  
    }
}
.express img 
{
    width:50px;
}
.deal 
{
   margin-top:-2px;
}

.deal img 
{
    width:60px;
}
.amazon img 
{
    width:100px;
}
.amazon 
{
    margin-top:13px;
}
 .fee 
    {
      
        background-color:gray;
        padding:5px 25px;
        color:white;
        border-radius:3px;
        
    }
</style>