<template>
  <v-card 
    color="white" 
   light
   background="white"
  elevation="0 px"> <!--colour for the card-->
    <v-toolbar 
      color="white"
      elevation="0 px"
    >
      <template >
        <v-tabs
          v-model="tabs"
          color="cyan lighten-1"
          
        ><!--naming each tab-->
          <v-tab class="smallbody"
            >
            Description
          </v-tab>
           <v-tab class="smallbody"
            >
            Specification
          </v-tab>
           <v-tab class="smallbody"
            >
            Brand
          </v-tab>
        </v-tabs>
      </template>
    </v-toolbar>
     <!--entering thwe content for the tabs-->
    <v-tabs-items v-model="tabs">
      <v-tab-item>
        <v-card flat
       
        color="#fff">
          <v-card-text>
           <div>
            <p class="tabtext justifytext">
            The iPhone 11 is a smartphone designed, developed, and marketed by Apple Inc. It is the thirteenth generation lower-priced iPhone, succeeding the iPhone XR. It was unveiled on September 10, 2019, alongside the higher-end iPhone 11 Pro flagship at the Steve Jobs Theater in Apple Park, Cupertino by Apple CEO Tim Cook. Pre-orders began on September 13, 2019, and the phone was officially released on September 20, 2019, one day after the official public release of iOS 13.
            </p>
           </div>
          </v-card-text>
        </v-card>
      </v-tab-item>
      <v-tab-item>
        <v-card flat class="tabtext"
        
        color="#fff">
           <!-- to asssign the text of specification-->
          <v-card-text>
           
          
            <p class="tabtext justifytext">
              Display              6.1-inch Liquid Retina HD display with True Tone <br>

              Width   :                75.7 mm (2.98 inches)<br>

              Depth   :               8.3 mm (0.33 inches) <br>


             Height   :              150.9 mm (5.94 inches)<br>

             Weight     :           194 grams (6.84 ounces) <br>

             Capacity    :         64GB    <br>

             Resistant    :        Water resistant to a depth of 2 metres for up to 30 minutes (IP68)
                                 Dust Resistant<br>

             Camera & video:          Dual 12MP cameras (Ultra Wide, Wide) with Portrait mode, Night mode, Auto Adjustments,
                                      next-generation Smart HDR and 4K video up to 60 fps with extended dynamic range<br>

             Front Camera     :             12MP TrueDepth front camera with Portrait mode, Smart HDR, 4K video recording
                                   up to 60 fps and slo-mo video support for 1080p at 120 fps <br>

             Power & Battery         :       Up to 17 hours video playback; up to 10 hours video streaming<br>

             In the Box   :        iPhone, EarPods with Lightning Connector, Lightning to USB Cable, 
                                 5W USB Power Adapter, Documentation <br>

             Warranty :          1 year manufacturer warranty for device and 6 months manufacturer warranty for 
                                 in-box accessories including batteries from the date of purchase<br>
           </p>
           
          </v-card-text>
        </v-card>
      </v-tab-item>
      <v-tab-item>
        <v-card flat
        color="#fff"
       dark>
          <v-row 
           class="col-lg-12 col-sm-12 col-xs-12">
        <v-col
          md="6"
          
          class=" tabtext col-xs-5 col-sm-9 col-md-9 col-lg-9 "
           offset-md="0"
           >
           <v-card-text
           >
           <div><!--text for brand details-->
            <p class="tabtext justifytext">
              Apple Inc. is an American multinational technology company headquartered in Cupertino, California, that designs, develops, and sells consumer electronics, computer software, and online services. It is considered one of the Big Tech technology companies, alongside Amazon, Google, Microsoft, and Facebook.

              The company's hardware products include the iPhone smartphone, the iPad tablet computer, the Mac personal computer, the iPod portable media player, the Apple Watch smartwatch, the Apple TV digital media player, the AirPods wireless earbuds and the HomePod smart speaker. Apple's software includes macOS, iOS, iPadOS, watchOS.
            </p>
            </div>
          </v-card-text>
         </v-col>
        
          <v-col       
             
             
              class=" col-xs-2 col-sm-3 col-md-2 col-lg-3 ">
              <!--placing image and text int he same row-->
              
           <v-img
             class="white--text align-end"
              src="https://www.freepnglogos.com/uploads/apple-logo-png/apple-logo-png-apple-grey-logo-png-transparent-pngpix-24.png"
             :width="$vuetify.breakpoint.xs 
                ? '230px' 
                : ($vuetify.breakpoint.sm
                    ? '400px' 
                    : ($vuetify.breakpoint.md
                        ? '600px'
                        : ($vuetify.breakpoint.lg
                            ? '200px' 
                            : '800px'
                        )
                    )
                )"
         
          ></v-img>
         
              
         
             
           </v-col>
         
        
        </v-row>
          
        </v-card>
      </v-tab-item>
    </v-tabs-items
    <span class="black--text">
  </v-card>
</template>

<style>
.tabtext { /*smaller detail body font stylingin black*/
    color: black;
    font-size: 14px;
    font-family:lato;

  }
  

</style>

<script>
  export default {
    data ()
     {
      return {
        tabs: null,
        text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',
      }
    },
  }
  
</script>