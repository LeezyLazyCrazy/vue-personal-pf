<template>
    <v-app 
    id="home" 
    :style="{ background: $vuetify.theme.themes.light.background}"
    >
    <Navbar />

    <!-- 1st section : kinda about skils page-->
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="1.png" contain max-height="600"></v-img>
        </v-col>
        <v-col cols="6">
          <h3 class="red-text text--darken-4 top">💻 Hello 👋🏻 This is Leezy </h3>
          <h1 class="outline"> { Front-end Developer } </h1>
          <h5 class="red-text text--darken-4"> 
            사람은 믿어주는 만큼 자라고<br /> 아껴주는 만큼 여물고<br /> 
            인정받는 만큼 성장하는 법<br />
            내가 선택한 주변 환경과 생각들에 따라 엄청난 결과의 차이를 만들 수 있다고 말이다<br />
          #create #passion #develope #dive #travell #drawing #netflix #pilates #dance <br /> 
          <br />
          </h5>
          <!-- <v-btn tile color="#f4d2f7" light>about me</v-btn> -->
        </v-col>
    <!-- 1st section  End -->

    <!-- 2nd section : project -->
      <div class="first" id="project"> 
        <v-row>
        <v-col md="3" offset-md="3">
            <v-card 
              class="pa-2 py-12" 
              outlined 
              tile 
              height="250px" 
              color="#1E1E1E">
            <v-img src="3.png" contain></v-img>
            </v-card>
        </v-col>

        <v-col md="3">
            <v-card 
              class="pa-2 py-12" 
              outlined 
              tile 
              height="250px" 
              color="#1E1E1E">
            <v-img src="2.png" contain ></v-img>
            </v-card>
        </v-col>

        <v-col md="3" offset-md="3">
            <v-btn color="white" dark text class="ml-n4">
              The Vintage
            </v-btn><br />
            <v-btn color="#EEFF41" dark text class="ml-n4">
              Know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>

        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4">
            Foodasa
          </v-btn><br />
          <v-btn color="#EEFF41" dark text class="ml-n4">
            Know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>

        <v-col md="3" offset-md="3">
          <v-card 
            class="pa-2 py-12" 
            outlined 
            tile 
            height="250px" 
            color="#1E1E1E">
            <v-img src="4.png" contain ></v-img>
          </v-card>
        </v-col>

        <v-col md="3">
          <v-card 
            class="pa-2 py-12" 
            outlined 
            tile 
            height="250px" 
            color="#1E1E1E">
          <v-img src="5.png" contain ></v-img>
          </v-card>
        </v-col>

        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4">
            AAE IdeaPro
          </v-btn><br />
          <v-btn color="#EEFF41" dark text class="ml-n4">
            Know more
          <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>

        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4">
            Mozaik
          </v-btn><br />
          <v-btn color="#EEFF41" dark text class="ml-n4">
            Know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        </v-row>   
      </div>  
    <!-- 2nd section End -->

    <!-- 3rd section : about -->
      <div class="second" id="about">
        <v-col cols="12" sm="4">
        </v-col>
          <v-row>
            <v-col md="3" offset-md="3">

            </v-col>
          </v-row>
      </div>
    <!-- 3rd section End -->

    <!-- 4rd section : contact -->
      <div class="third" id="contact">    
        <v-col cols="12" sm="4" >     
          </v-col>
            <v-card-text class="pt-2"  >
              <v-btn 
                v-for="icon in icons" 
                :key="icon" 
                class="mx-4 white--text" 
                icon
              >
                <v-icon size="24px">{{ icon }}</v-icon>
              </v-btn>
            </v-card-text>
      </div>
    <!-- 4rd section End -->
     </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>


<script>
  import Navbar from '../components/Navbar'
  import Footer from '../components/Footer'

  export default {
    name: 'Home',
    data: ()=> ({
      icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
    }),

    components: {
      Navbar,
      Footer
    },
  };
</script>

<style scoped>
.outline {
  color: #FFFFFF;
  text-shadow: 2px 2px 0 #0d7dde, 2px -2px 0 #0d7dde, -2px 2px 0 #0d7dde, -2px -2px 0 #0d7dde, 2px 0px 0 #0d7dde, 0px 2px 0 #0d7dde, -2px 0px 0 #0d7dde, 0px -2px 0 #0d7dde;
}
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(
    to bottom,
    #ffd54f,
    #ffd54f 10%,
    #fdd550 30%,
    #fac042 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}

.second {
  width: 100%;
  height: 400px;
  background:#f7c04b;
  text-align: center;
  padding: 2rem 2rem;
}

</style>