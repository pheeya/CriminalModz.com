<template>
<div class="main">
    <div class="cards">
         <cmp-card 
         title='24/7 CUSTOMER SERVICE'
         imgLink="https://i1.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Untitled-2-3.png?fit=500%2C500&amp;ssl=1" class="attachment-full size-full jetpack-lazy-image jetpack-lazy-image--handled" alt="Customer service" srcset="https://i1.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Untitled-2-3.png?w=500&amp;ssl=1 500w, https://i1.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Untitled-2-3.png?resize=150%2C150&amp;ssl=1 150w, https://i1.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Untitled-2-3.png?resize=300%2C300&amp;ssl=1 300w" data-lazy-loaded="1" sizes="(max-width: 500px) 100vw, 500px"
         content='We care about our Customers and more 
                 than 64 agents are here to provide top notch assistance!'
         ></cmp-card>
         
         <cmp-card 
         title='100% LEGIT SERVICE'
         imgLink="https://i0.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Untitled-2-5.png?w=500&ssl=1 300w" data-lazy-loaded="1" sizes="(max-width: 500px) 100vw, 500px"
         content = 'We currently serve for more 10000+ satisfied customers and increasing daily on size with 500+ Reviews.'
         ></cmp-card>
          <cmp-card 
         title='EXPERIENCED MODDER TEAM'
         imgLink="https://i1.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Untitled-2-4.png?w=500&ssl=1 300w" data-lazy-loaded="1" sizes="(max-width: 500px) 100vw, 500px"
         content = 'Every Modder of ours has modded more than 15.000 Accounts with no Bans!'
         ></cmp-card>
         <!---------------------------------------------------->
          <cmp-card 
         title='FREE TRIAL BEFORE YOU BUY'
         imgLink="https://i0.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Untitled-2-7.png?w=500&ssl=1 300w" data-lazy-loaded="1" sizes="(max-width: 500px) 100vw, 500px"
         content = 'Are you not sure if you want to purchase? No problem! You can 
check out our Service for FREE.'
         ></cmp-card>
          <!---------------------------------------------------->
          <cmp-card 
         title='FAST & EASY DELIVERY'
         imgLink="https://i2.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Untitled-1-24.png?w=500&ssl=1 300w" data-lazy-loaded="1" sizes="(max-width: 500px) 100vw, 500px"
         content = 'Receive all Services within a fast timeframe that you can select at the checkout.'
         ></cmp-card>
           <!---------------------------------------------------->
          <cmp-card 
         title='FREE TRIAL BEFORE YOU BUY'
         imgLink="https://i0.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Untitled-1-25.png?w=500&ssl=1 300w" data-lazy-loaded="1" sizes="(max-width: 500px) 100vw, 500px"
         content = 'With every service you purchase you automatically receive a Ban Warranty for free!'
         ></cmp-card>
         <!---------------------------------------------------->
          <cmp-card 
         title='ORDER STATUS'
         imgLink="https://i1.wp.com/criminalmodz.com/wp-content/uploads/2019/04/Untitled-1-26.png?w=500&ssl=1 300w" data-lazy-loaded="1" sizes="(max-width: 500px) 100vw, 500px"
         content = 'CriminalModz offers you the chance to track your order all the time, unlike other sites that leave you in the dark.'
         ></cmp-card>
         
    </div>
    </div>
</template>

<script>
import card from "./card"
export default {
 components:{
     cmpCard:card
 }   
}
</script>

<style scoped>
.cards 
{
      display:grid;
    grid-template-columns: 50% 50%;
}
.main 
{
  font-size:15px;
  color:rgb(92, 92, 92);
  line-height: 2;
}
</style>