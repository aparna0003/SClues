<template>
  <v-card
   color="#EDF8F9"
    v-scroll.self="onScroll"
    class="overflow-y-auto"
    max-height="300"
    width="1200"
  >
    
    <v-card-text>
      <div
        v-for="n in 1"
        :key="n"
        class="mb-4"
      >
       <p>
       <p>
       
     <span class= " question"> 
          How old is the stock? <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
         The last stock was acquired two months back 
      </span>
       </p>

       <p>       
     <span class= " question"> 
          When will next set of stock be available? <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
          The next slot will be available within four days
      </span>
       </p>

        <p>       
     <span class= " question"> 
          Where is you distribution center? <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
          We are providing all over India 
      </span>
       </p>

        <p>       
     <span class= " question"> 
         Are you providing colour variations? <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
          We have all the colour variation available according tot the stock. Please look for the 
          needful color specifically
      </span>
       </p>

       <p>       
     <span class= " question"> 
          How much time does it take for transportation? <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
           About a week 
      </span>
       </p>

       <p>       
     <span class= " question"> 
          When all do you provide offer<br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
          Mostly offer 
      </span>
       </p>

       <p>       
     <span class= " question"> 
          Is 162GB available <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
          please check in our other products
      </span>
       </p>

       <p>       
     <span class= " question"> 
          How to contact you <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
          84203514452
      </span>
       </p>

       <p>       
     <span class= " question"> 
          Are you providing warrenty <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
         yes 1 year warrenty
      </span>
       </p>

        <p>       
     <span class= " question"> 
         is warranty extension provided by you  <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
        if you join our membership you will be provided after a certain procedure
      </span>
       </p>

        <p>       
     <span class= " question"> 
         Are there extra charges for transportation   <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
        It is included
      </span>
       </p>

        <p>       
     <span class= " question"> 
         Is there any hidden cost  <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
       No. We make sure of that
      </span>
       </p>

        <p>       
     <span class= " question"> 
         is iPencil compatible with iPhone 11  <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
       No. it is not
      </span>
       </p>

        <p>       
     <span class= " question"> 
         Can you provide more detailed info <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
        Sure. Please contact us in 15525415528
      </span>
       </p>

        <p>       
     <span class= " question"> 
         I have ordered it already but its taking forever <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
      Could you please provide you Purchase Id with us
      </span>
       </p>

        <p>       
     <span class= " question"> 
         When to expect for delivery after purcgase ? <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
        Over a week
      </span>
       </p>

        <p>       
     <span class= " question"> 
         If the product sent to us is damaged will I get  a refund or exchange  <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
       Sure actions will be taken according to the situation
      </span>
       </p>

        <p>       
     <span class= " question"> 
        How do you transport  <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
        ShopClues stays the transportation medium generally 
      </span>
       </p>

        <p>       
     <span class= " question"> 
         For how long have you been in this buisness? <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
       About a decade
      </span>
       </p>

        <p>       
     <span class= " question"> 
         Are you varified  <br>
      </span>
       <span class= " question"> 
          Ans: 
      </span>
      <span class= " answer"> 
        yes we are
      </span>
       </p>

       

       </p>
         
       
      </div>
    </v-card-text>
  </v-card>
</template>


<script>
  export default {
    data: () => ({
      scrollInvoked: 0,
    }),

    methods: {
      onScroll () {
        this.scrollInvoked++
      },
    },
  }
</script>