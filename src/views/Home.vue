<template>
  <v-app id="home" :style="{ background: $vuetify.theme.themes.light.background }">
    <Navbar />

    <!-- 1st section : kinda about skils page-->
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="1.png" contain max-height="600"></v-img>
        </v-col>
        <v-col cols="6">
          <h3 class="red-text text--darken-4 top">💻 Hello 👋🏻 This is Leezy</h3>
          <div class="outline"><h1>{ Front-end Developer }</h1></div>
          <h5 class="red-text text--darken-4">
            사람은 믿어주는 만큼 자라고<br />
            아껴주는 만큼 여물고<br />
            인정받는 만큼 성장하는 법<br />
            내가 선택한 주변 환경과 생각들에 따라 <br />
            엄청난 결과의 차이를 만들 수 있다고 말이다<br />
            <div class="hashtag">
              <MARQUEE scrolldelay="200" width="400" height="30" hspace="50" vspace="50" bgColor="blue" behavior="scroll" loop="3">
                #ISFP-T #create #passion #develope #dive #travell #drawing #netflix #pilates #dance
              </MARQUEE>
            </div>
          </h5>
          <!-- <v-btn tile color="#f4d2f7" light>about me</v-btn> -->
        </v-col>
        <!-- 1st section  End -->

        <!-- 2nd section : project -->
        <div class="first" id="project">
          <v-row>
            <v-col md="3" offset-md="3">
              <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
                <v-img src="3.png" contain></v-img>
              </v-card>
            </v-col>

            <v-col md="3">
              <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
                <v-img src="2.png" contain></v-img>
              </v-card>
            </v-col>

            <v-col md="3" offset-md="3">
              <v-btn color="white" dark text class="ml-n4"> The Vintage </v-btn><br />
              <v-btn color="#EEFF41" dark text class="ml-n4">
                Know more
                <v-icon right>mdi-arrow-right</v-icon>
              </v-btn>
            </v-col>

            <v-col md="3">
              <v-btn color="white" dark text class="ml-n4"> Foodasa </v-btn><br />
              <v-btn color="#EEFF41" dark text class="ml-n4">
                Know more
                <v-icon right>mdi-arrow-right</v-icon>
              </v-btn>
            </v-col>

            <v-col md="3" offset-md="3">
              <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
                <v-img src="4.png" contain></v-img>
              </v-card>
            </v-col>

            <v-col md="3">
              <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
                <v-img src="5.png" contain></v-img>
              </v-card>
            </v-col>

            <v-col md="3" offset-md="3">
              <v-btn color="white" dark text class="ml-n4"> AAE IdeaPro </v-btn><br />
              <v-btn color="#EEFF41" dark text class="ml-n4">
                Know more
                <v-icon right>mdi-arrow-right</v-icon>
              </v-btn>
            </v-col>

            <v-col md="3">
              <v-btn color="white" dark text class="ml-n4"> Mozaik </v-btn><br />
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
          <v-col md="3" offset-md="3"> </v-col>
          <v-row>
            <v-col md="3" offset-md="3">
              <div class="allaboutme" subtitle-1>
                <h2>I can be anything</h2>
              </div>
            </v-col>
          </v-row>
        </div>
        <!-- 3rd section End -->

        <!-- 4th section : contact -->
        <div class="third" id="contact">
          <v-col cols="12" sm="4"> </v-col>
          <v-card-text class="pt-0">
            <v-btn v-for="icon in icons" :key="icon" class="mx-4 white--text justify-space-around" icon @click="icon.path">
              <v-icon size="24px">{{ icon.name }}</v-icon>
            </v-btn>
          </v-card-text>
        </div>
        <!-- 4th section End -->
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
  import Navbar from '../components/Navbar';
  import Footer from '../components/Footer';

  export default {
    name: 'Home',
    data() {
      return {
        icons: [
          {
            name: 'mdi-chat',
            path: () => {
              this.moveToOpenchat();
            },
          },
          {
            name: 'mdi-github',
            path: () => {
              this.moveToGithub();
              console.log('click');
            },
          },         
          {
            name: 'mdi-linkedin',
            path: () => {
              this.moveToLinkedIn();
            },
          },
          {
            name: 'mdi-gmail',
            path: () => {
              this.moveToGmail();
            },
          },
        ],
      };
    },

    components: {
      Navbar,
      Footer,
    },

    methods: {
      moveToOpenchat() {
        window.open('https://open.kakao.com/o/sBKP7N5d', '_blank');
      },
      moveToGithub() {
        window.open('https://github.com/LeezyLazyCrazy', '_blank');
      },
      moveToLinkedIn() {
        window.open('https://www.linkedin.com/in/leejiwonvsc/', '_blank');
      },
      moveToGmail() {
        window.open('mailto:leeg1dance@gmail.com', '_blank');
      },
    },
  };
</script>

<style scoped>
  #home {
    background: linear-gradient(to bottom, #ffd54f, #ffd54f 10%, #fdd550 30%, #fac042 50%);
  }
  .outline {
    color: rgb(250, 250, 250);
    text-shadow: 2px 2px 0 #0d7dde, 2px -2px 0 #0d7dde, -2px 2px 0 #0d7dde, -2px -2px 0 #0d7dde, 2px 0px 0 #0d7dde, 0px 2px 0 #0d7dde,
      -2px 0px 0 #0d7dde, 0px -2px 0 #0d7dde;
  }
  .hashtag {
    margin-top: 20px;
    font-size: 20px;
    align-content: center;
    color: rgb(250, 250, 250);
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
    background: linear-gradient(#ffd54f, #ffd54f 20%, #facf43 40%, #fcc244 60%);
    text-align: center;
    padding: 2rem 2rem;
  }

  .second {
    width: 100%;
    height: 400px;
    background: #fac042;
    text-align: center;
    padding: 2rem 2rem;
  }
  .third {
    background: #fac042;
  }
</style>