<template>
  <v-app id="home" :style="{ background: $vuetify.theme.themes.light.background }">
    <Navbar />

    <!-- 1st section : intro page-->
    <v-container fluid>
      <v-row>
      <div class="first" id="intro">
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
      </div>     
        <!-- 1st section  End -->

        <!-- 2nd section : project -->
        <!-- <div class="second" id="project">
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
        </div> -->
        <!-- 2nd section End -->

      <div class="second " id="project">
        <Portfolio/>
        <v-row class="justify-space-around m-4">
          <v-col cols="3" class="pf-box">
           
              <div class="pfIcon">
                <p class="icon">
                  <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                  <img src="https://img.icons8.com/carbon-copy/100/000000/partly-cloudy-night.png"/>
                  </a>
                </p>
                <div id="desc">
                  <h4>Weather API</h4>
                  <span class="site">
                    <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                    <img src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/30/000000/external-web-business-management-kmg-design-basic-outline-kmg-design.png"/>
                    </a>
                  </span>
                  <span class="github">
                    <a href="https://github.com/LeezyLazyCrazy/vue3-weather-api.git" target="blank">
                    <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png"/>
                    </a>
                  </span>
              </div>           
            </div>
            <div class="techIcon">Technologies Used
              <div class="tech_img">
                 <img src="https://img.icons8.com/windows/32/000000/vuejs.png"/>
                 <img src="https://img.icons8.com/ios/50/000000/javascript--v1.png"/>
                 <img src="https://img.icons8.com/ios/32/000000/sass.png"/>
              </div>             
            </div>
           

            
            
          </v-col>
          <v-col cols="3">
            <div class="pfIcon">
              <p class="icon">
                <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                <img src="https://img.icons8.com/carbon-copy/100/000000/partly-cloudy-night.png"/>
                </a>
              </p>
              <div id="desc">
                <h4>Weather API</h4>
                <span class="site">
                  <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                  <img src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/32/000000/external-web-business-management-kmg-design-basic-outline-kmg-design.png"/>
                  </a>
                </span>
                <span class="github">
                  <a href="https://github.com/LeezyLazyCrazy/vue3-weather-api.git" target="blank">
                  <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png"/>
                  </a>
                </span>
              </div>           
            </div>
            <div class="techIcon">Technologies Used
              <div class="tech_img">
                 <img src="https://img.icons8.com/windows/32/000000/vuejs.png"/>
                 <img src="https://img.icons8.com/ios/50/000000/javascript--v1.png"/>
                 <img src="https://img.icons8.com/ios/32/000000/sass.png"/>
              </div>
                
            </div>
          </v-col>
           <v-col cols="3">
            <div class="pfIcon">
              <p class="icon">
                <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                <img src="https://img.icons8.com/carbon-copy/100/000000/partly-cloudy-night.png"/>
                </a>
              </p>
              <div id="desc">
                <h4>Weather API</h4>
                <span class="site">
                  <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                  <img src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/32/000000/external-web-business-management-kmg-design-basic-outline-kmg-design.png"/>
                  </a>
                </span>
                <span class="github">
                  <a href="https://github.com/LeezyLazyCrazy/vue3-weather-api.git" target="blank">
                  <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png"/>
                  </a>
                </span>
              </div>           
            </div>
            <div class="techIcon">Technologies Used
              <div class="tech_img">
                 <img src="https://img.icons8.com/windows/32/000000/vuejs.png"/>
                 <img src="https://img.icons8.com/ios/50/000000/javascript--v1.png"/>
                 <img src="https://img.icons8.com/ios/32/000000/sass.png"/>
              </div>
                
            </div>
          </v-col>
        </v-row>
        <v-row class="justify-space-around m-4">
          <v-col cols="3">
            <div class="pfIcon">
              <p class="icon">
                <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                <img src="https://img.icons8.com/carbon-copy/100/000000/partly-cloudy-night.png"/>
                </a>
              </p>
              <div id="desc">
                <h4>Weather API</h4>
                <span class="site">
                  <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                  <img src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/32/000000/external-web-business-management-kmg-design-basic-outline-kmg-design.png"/>
                  </a>
                </span>
                <span class="github">
                  <a href="https://github.com/LeezyLazyCrazy/vue3-weather-api.git" target="blank">
                  <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png"/>
                  </a>
                </span>
              </div>           
            </div>
            <div class="techIcon">Technologies Used
              <div class="tech_img">
                 <img src="https://img.icons8.com/windows/32/000000/vuejs.png"/>
                 <img src="https://img.icons8.com/ios/50/000000/javascript--v1.png"/>
                 <img src="https://img.icons8.com/ios/32/000000/sass.png"/>
              </div>
                
            </div>
          </v-col>
          <v-col cols="3">
            <div class="pfIcon">
              <p class="icon">
                <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                <img src="https://img.icons8.com/carbon-copy/100/000000/partly-cloudy-night.png"/>
                </a>
              </p>
              <div id="desc">
                <h4>Weather API</h4>
                <span class="site">
                  <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                  <img src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/32/000000/external-web-business-management-kmg-design-basic-outline-kmg-design.png"/>
                  </a>
                </span>
                <span class="github">
                  <a href="https://github.com/LeezyLazyCrazy/vue3-weather-api.git" target="blank">
                  <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png"/>
                  </a>
                </span>
              </div>           
            </div>
            <div class="techIcon">Technologies Used
              <div class="tech_img">
                 <img src="https://img.icons8.com/windows/32/000000/vuejs.png"/>
                 <img src="https://img.icons8.com/ios/50/000000/javascript--v1.png"/>
                 <img src="https://img.icons8.com/ios/32/000000/sass.png"/>
              </div>
                
            </div>
          </v-col>
           <v-col cols="3">
            <div class="pfIcon">
              <p class="icon">
                <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                <img src="https://img.icons8.com/carbon-copy/100/000000/partly-cloudy-night.png"/>
                </a>
              </p>
              <div id="desc">
                <h4>Weather API</h4>
                <span class="site">
                  <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                  <img src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/32/000000/external-web-business-management-kmg-design-basic-outline-kmg-design.png"/>
                  </a>
                </span>
                <span class="github">
                  <a href="https://github.com/LeezyLazyCrazy/vue3-weather-api.git" target="blank">
                  <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png"/>
                  </a>
                </span>
              </div>           
            </div>
            <div class="techIcon">Technologies Used
              <div class="tech_img">
                 <img src="https://img.icons8.com/windows/32/000000/vuejs.png"/>
                 <img src="https://img.icons8.com/ios/50/000000/javascript--v1.png"/>
                 <img src="https://img.icons8.com/ios/32/000000/sass.png"/>
              </div>
                
            </div>
          </v-col> 
        </v-row>       
      </div>


        <v-col cols="12">
          <v-row>
        <!-- 3rd section : about -->
            <div class="third mt-4 p-8" id="about">
              <h1>ABOUT ME</h1>       
                <p class="emoji mt-6">👩🏻‍💻</p>
                <h3>I'm a Flexible Developer</h3>
                <p class="mt-2">끊임 없이 기초를 습득하고, 도전하며 IT기술과 문화의 현재 동향 그리고 미래의 트렌드를 항상 체크하는 프론트엔드 개발자 이지원입니다.</p>
                <p>#날것의 #스펀지같은상태 #센스탑재</p> 
                        
                <p class="emoji t-6">👀</p> 
                <p>Site: freecodecamp,  techcrunch, ttime, ITWORLD</p>
                <p>Youtube: Traversy Media, Nomad coders,eo, 드림코딩by엘리 </p> 
            </div>
          </v-row>
        </v-col>
       <!-- 3rd section End -->
        <v-col cols="12">
          <v-row>
        <!-- 4th section : contact -->
            <div class="fourth" id="contact">
              <h1>CONTACK</h1>    
              <v-btn 
                    v-for="icon in icons" 
                    :key="icon" 
                    class="justify-space-around mt-8 ml-6 mr-6" 
                    icon @click="icon.path"
              >
              <v-icon size="30px" color="#c739ff">{{ icon.name }}</v-icon>
              </v-btn>
              <h2> 👆🏻 </h2>
              <div id="text">
                  <h3>"If you want know me then CLICK!!" </h3>
                  <h3>"Grab a cup of Coffee?  then CLICK!!"</h3>  
              </div>        
            </div> 
        <!-- 4th section End -->
          </v-row>
        </v-col>
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
      moveToGmail() {
        window.open('mailto:leeg1dance@gmail.com', '_blank');
      },
    },
  };
</script>


<style lang="scss">
   #home {
    background: #ffe600;
  }
  .first {
    display:flex;
    width:100%;
    height: 100%;
  }
  .outline {
    color: rgb(250, 250, 250);
    text-shadow: 2px 2px 0 #c739ff, 2px -2px 0 #c739ff, -2px 2px 0 #c739ff, -2px -2px 0 #c739ff, 2px 0px 0 #c739ff, 0px 2px 0 #c739ff,
      -2px 0px 0 #c739ff, 0px -2px 0 #c739ff;
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
  .second {
    width: 100%;
    height: auto;
    text-align: center;
    padding: 2rem 2rem;
    .pf-box {
      border: 3px solid #010146;
      border-radius: 20px;
    }
      .pfIcon {
      display: flex;
      justify-content:center;    
      p{
        border: 1px solid #c739ff;
        border-radius: 30px;
      }
      #desc{
        padding-left: 5px;  
        h4 {
          margin-bottom: 12px;
        }   
        span{
          margin:0 5px; 
            img{
            height:25px;
            width: 25px;
                  }
        }
      }
      }
    #desc {
      margin: 20px 5px;
    }
    .techIcon .tech_img{
      margin-top: 10px;
      img{
        height: 35px;
        width:35px;
        margin-left: 4px;

      }
    }
  }


  
 p {
   
    flex-direction: row;
  }
  .third {
    width: 100%;
    text-align: center;
    padding: 2rem 2rem;
    color: #030331;
  }
  .third .emoji{
    font-size: 1.5rem;
  }
  .third h1{
    color:#010146;
    }
  .third h3{
    color:#c739ff;
    }
  .third h5{
    color:#c739ff;
    }
 
  .fourth {
    width: 100%;
    text-align: center;
    padding: 2rem 2rem;
    color:#010146;
  }
  .fourth h2 {
    margin-top: 30px;
  }
  .fourth h3{
    margin-top: 10px;
  }

</style> 

