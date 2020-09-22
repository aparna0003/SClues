<template>
  <v-container class="grey lighten-5">
    <v-row no-gutters>
      <v-col
        v-for="n in 3"
        :key="n"
        cols="12"
        md="4"
      >
        <v-card
          class=" ms-3 pa-2"
          outlined
          tile
        >
           <v-img
           height="550"
           src="https://images.unsplash.com/photo-1577720086684-eb7be1e40721?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60"
         ></v-img>
        </v-card>
      </v-col>
    </v-row>
    <v-row no-gutters>
      <v-col
       
        cols="12"
        md="4"
      >
        <v-card
          class=" ms-4 mt-2 pa-2 "

          outlined
          :key="1"
          tile
        >
          <v-img
         
           src="https://www.hindustantimes.com/rf/image_size_444x250/HT/p2/2017/05/20/Pictures/_9907eb42-3d47-11e7-99bd-b9a47f5fadca.jpg"
         ></v-img>
          
          
        </v-card>
      </v-col>
      <v-col>        
       <v-card
          class="  ms-2 mt-2 pa-2 "

          outlined
          :key="2"
          tile
        ><v-img
        
           src="https://www.tintin.com/tintin/albums/02amerique/amerique.jpg"
         ></v-img>
         
         </v-card>
        </v-col>
       <v-col>        
       <v-card
          class="  ms-2 mt-2 pa-2 "

          outlined
          :key="2"
          tile
        ><v-img
           
           src="https://www.tintin.com/tintin/persos/tintin/tintin.jpg"
         ></v-img>
         
         </v-card>
        </v-col>
    </v-row>
      </v-row>
    <v-row no-gutters>
      <v-col
       
        cols="12"
        md="6"
      >
        <v-card
          class=" cyan lighten-1 ms-4 mt-2 pa-2 "

          outlined
          :key="1"
          tile
        >
          <v-img
         
           src="https://i.pinimg.com/originals/dc/92/3e/dc923eb9bfc95bb18ecea3875fc3bb31.jpg"
         ></v-img>
          
          
        </v-card>
      </v-col>
      <v-col>        
       <v-card
          class=" cyan lighten-0 ms-2 mt-2 pa-8 "

          outlined
          :key="2"
          tile
        >
          Tintin in America <br         >
           Story<br>
          In Tintin in America (1932), Tintin confirms his reputation as a righter of wrongs. He faces Al Capone and his gang as 
          well as all sorts of other villains. Hergé shows his generous vision of the world as he offers a very well documented 
          depiction of the sad plight of the Native Americans. Tintin's fame extends beyond the Atlantic Ocean, so, when he arrives 
          in Chicago in the middle of Prohibition, all the gangsters in the city have gathered to make sure that he gets the most
          uncomfortable reception. Tintin will need to use all his determination and intelligence to survive! Tintin in America is 
          the highest-selling Tintin title of all time. It is the clear winner ahead of Tintin in the Congo and Explorers on the 
          Moon, which come in second and third places respectively.
          </p>

          A cover story<br >
          <p>Tintin books have not always looked like they do today. At the beginning of Hergé's career, The Adventures of Tintin
           were published with a variety of different covers. The first edition of Tintin in America rolled off the printing press 
           in 1932. The cover picture showed Tintin sitting on a rock while Red Indians creep up behind him, and the original 
           Indian ink and gouache drawing was recently sold in auction for an astronomical price. The book was titled Les Aventures
            de Tintin, reporter du Petit "Vingtième" in America.
         <p>

          <p>In November 1937, the adventure was published under a new cover adorned with a small picture showing Tintin riding a horse. 
          The publisher's name, Casterman, (which was already printed in the 1935 edition) is also mentioned in this copy. Tintin in America
          </p>
         </v-card>
        </v-col>
    </v-row>
  </v-container>
</template>
<script>
  export default {
    data: () => ({
      //
    }),
  }
</script>