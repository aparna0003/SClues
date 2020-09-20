<template>
  <v-card>
    <v-toolbar
      color="#55BCC9"
      
      flat
      prominent
    >
      

      <template v-slot:extension>
        <v-tabs
          v-model="tabs"
          centered
        >
          <v-tab
            v-for="n in 3"
            :key="n"
          >
            Description
          </v-tab>
        </v-tabs>
      </template>
    </v-toolbar>

    <v-tabs-items v-model="tabs">
      <v-tab-item>
        <v-card flat>
          <v-card-text>
            The iPhone 11 is a smartphone designed, developed, and marketed by Apple Inc. It is the thirteenth generation lower-priced iPhone, succeeding the iPhone XR. It was unveiled on September 10, 2019, alongside the higher-end iPhone 11 Pro flagship at the Steve Jobs Theater in Apple Park, Cupertino by Apple CEO Tim Cook. Pre-orders began on September 13, 2019, and the phone was officially released on September 20, 2019, one day after the official public release of iOS 13.
          </v-card-text>
        </v-card>
      </v-tab-item>
      <v-tab-item>
        <v-card flat>
          <v-card-title class="headline">An awesome title</v-card-title> <!-- to asssign the text of specification-->>
          <v-card-text>
            <p>
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
        <v-card flat>
          <v-row>
        <v-col
          md="5"
           class="ml-md-auto"
           offset-md="0"
           >
           <v-card-text>
            <p>
              Apple Inc. is an American multinational technology company headquartered in Cupertino, California, that designs, develops, and sells consumer electronics, computer software, and online services. It is considered one of the Big Tech technology companies, alongside Amazon, Google, Microsoft, and Facebook.

              The company's hardware products include the iPhone smartphone, the iPad tablet computer, the Mac personal computer, the iPod portable media player, the Apple Watch smartwatch, the Apple TV digital media player, the AirPods wireless earbuds and the HomePod smart speaker. Apple's software includes macOS, iOS, iPadOS, watchOS.
            </p>
         
          </v-card-text>
         </v-col>
         <v-col
           md="3"
           class="ml-md-auto"
           offset-md="2"
           >
            <v-img
           height="350"
           src="https://wpgroupbuydemo.com/wp-content/uploads/2014/07/Apple_logo.png"
         ></v-img>
            
          </v-col>
        
        </v-row>
          
        </v-card>
      </v-tab-item>
    </v-tabs-items>
  </v-card>
</template>

<script>
  export default {
    data () {
      return {
        tabs: null,
        text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',
      }
    },
  }
</script>