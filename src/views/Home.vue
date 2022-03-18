<template>
  <v-app id="home" :style="{ background: $vuetify.theme.themes.light.background }">
    <Navbar />

<!-- 1st section : intro page-->
    <v-container fluid align-center>
      <v-row class="mt-14">
      <div class="first" id="intro">
        <v-col cols="6" >
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
        </v-col>
      </div>     
<!-- End of 1st section -->

<!-- 2nd section : project -->
      <div class="second " id="project">
        <h1>PROJECT</h1>
        <v-row class="pf justify-space-around mt-14 flex-{md}-{nowrap}">
          <v-col cols="3" class="pf-box">
              <div class="pfIcon">
                <p class="icon">
                  <a href="https://leezy-vuejs-weather.netlify.app" target="blank">
                  <img src="https://img.icons8.com/doodle/95/000000/summer.png"/>
                  </a>
                </p>
                <div id="desc">
                  <h3>Weather API Web</h3>
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
                 <img src="https://img.icons8.com/ios/32/000000/javascript--v1.png"/>
                 <img src="https://img.icons8.com/ios/32/000000/sass.png"/>
                 <img src="https://img.icons8.com/windows/32/000000/api-settings.png"/>
              </div>             
            </div>                        
          </v-col>
          <v-col cols="3" class="pf-box">  
              <div class="pfIcon">
                <p class="icon">
                  <a href="https://leezy-vuejs-movie.netlify.app" target="blank">
                  <img src="https://img.icons8.com/external-xnimrodx-lineal-color-xnimrodx/90/000000/external-video-online-marketing-xnimrodx-lineal-color-xnimrodx.png"/>
                  </a>
                </p>
                <div id="desc">
                  <h3>Movie API</h3>
                  <span class="site">
                    <a href="https://leezy-vuejs-movie.netlify.app" target="blank">
                    <img src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/30/000000/external-web-business-management-kmg-design-basic-outline-kmg-design.png"/>
                    </a>
                  </span>
                  <span class="github">
                    <a href="https://github.com/LeezyLazyCrazy/Vue3-MovieAPI-v1" target="blank">
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
                 <img src="https://img.icons8.com/windows/32/000000/api-settings.png"/>
                 <img src="https://img.icons8.com/windows/32/000000/bootstrap.png"/>
              </div>             
            </div>          
          </v-col>
          <v-col cols="3" class="pf-box">
              <div class="pfIcon">
                <p class="icon">
                  <a href="https://renewal-web.netlify.app/" target="blank">
                  <img src="https://img.icons8.com/external-flaticons-lineal-color-flat-icons/100/000000/external-camp-camping-flaticons-lineal-color-flat-icons-2.png"/>
                  </a>
                </p>
                <div id="desc">
                  <h3>Renewal Web</h3>
                  <span class="site">
                    <a href="https://renewal-web.netlify.app/" target="blank">
                    <img src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/30/000000/external-web-business-management-kmg-design-basic-outline-kmg-design.png"/>
                    </a>
                  </span>
                  <span class="github">
                    <a href="https://github.com/LeezyLazyCrazy/lbcamp_API-Project.git" target="blank">
                    <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png"/>
                    </a>
                  </span>
              </div>           
            </div>
            <div class="techIcon">Technologies Used
              <div class="tech_img">
                <img src="https://img.icons8.com/windows/32/000000/html-5.png"/>
                <img src="https://img.icons8.com/windows/32/000000/css-filetype.png"/>
                <img src="https://img.icons8.com/ios/50/000000/javascript--v1.png"/>
                <img src="https://img.icons8.com/windows/32/000000/api-settings.png"/>
                <img src="https://img.icons8.com/ios/32/000000/php-server.png"/>
                 
              </div>             
            </div>            
          </v-col>
        </v-row>
        <v-row class="pf justify-space-around mt-14" md="2">
          <v-col cols="3" class="pf-box">          
              <div class="pfIcon">
                <p class="icon">
                  <a href="https://squidgamedoll-threejs.netlify.app" target="blank">
                  <img src="squidgamedoll.png">
                  </a>
                </p>
                <div id="desc">
                  <h3>Squid Game Web</h3>
                  <span class="site">
                    <a href="https://squidgamedoll-threejs.netlify.app" target="blank">
                    <img src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/30/000000/external-web-business-management-kmg-design-basic-outline-kmg-design.png"/>
                    </a>
                  </span>
                  <span class="github">
                    <a href="https://github.com/LeezyLazyCrazy/squidgame_threejs_pf.git" target="blank">
                    <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png"/>
                    </a>
                  </span>
              </div>           
            </div>
            <div class="techIcon">Technologies Used
              <div class="tech_img">
                <img src="https://img.icons8.com/windows/32/000000/html-5.png"/>
                <img src="https://img.icons8.com/windows/32/000000/css-filetype.png"/>
                <img src="three-js-logo.png">
              </div>             
            </div>            
          </v-col>
          <v-col cols="3" class="pf-box">           
              <div class="pfIcon">
                <p class="icon">
                  <a href="https://leezy-vuejs-covid19tracker.netlify.app" target="blank">
                  <img src="https://img.icons8.com/external-flaticons-flat-flat-icons/90/000000/external-covid-vacation-planning-trip-abroad-flaticons-flat-flat-icons-2.png"/>
                  </a>
                </p>
                <div id="desc">
                  <h3>Covid Tracker API</h3>
                  <span class="site">
                    <a href="https://leezy-vuejs-covid19tracker.netlify.app" target="blank">
                    <img src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/30/000000/external-web-business-management-kmg-design-basic-outline-kmg-design.png"/>
                    </a>
                  </span>
                  <span class="github">
                    <a href="https://github.com/LeezyLazyCrazy/vue3-covidtracker-api.git" target="blank">
                    <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png"/>
                    </a>
                  </span>
              </div>           
            </div>
            <div class="techIcon">Technologies Used
              <div class="tech_img">
                <img src="https://img.icons8.com/windows/32/000000/vuejs.png"/>                
                <img src="https://img.icons8.com/windows/32/000000/html-5.png"/>
                <img src="https://img.icons8.com/windows/32/000000/css-filetype.png"/>
                <img src="https://img.icons8.com/ios/50/000000/javascript--v1.png"/>
                <img src="tailwind-logo.png" >             

              </div>             
            </div>            
          </v-col>
          <v-col cols="3" class="pf-box">           
              <div class="pfIcon">
                <p class="icon">
                  <a href="https://leezy-portfolio.netlify.app" target="blank">
                  <img src="pf.png">
                  </a>
                </p>
                <div id="desc">
                  <h3>Portfolio</h3>
                  <span class="site">
                    <a href="https://leezy-portfolio.netlify.app" target="blank">
                    <img src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/30/000000/external-web-business-management-kmg-design-basic-outline-kmg-design.png"/>
                    </a>
                  </span>
                  <span class="github">
                    <a href="https://github.com/LeezyLazyCrazy/personal-pf.git" target="blank">
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
                 <img src="vuetify.png">
              </div>             
            </div>           
          </v-col>
        </v-row>       
      </div>
<!-- End of 2nd section -->

<!-- 3rd section : about -->
        <v-col cols="12 mt-12">
          <v-row>       
            <div class="third mt-8 p-8" id="about">
              <h1>ABOUT ME</h1>       
                <p class="emoji mt-6">👩🏻‍💻</p>
                <h3>I'm a Flexible Developer</h3>
                <p class="mt-2">끊임 없이 기초를 습득하고, 도전하며 IT기술과 문화의 현재 동향 그리고 미래의 트렌드를 항상 체크하는 프론트엔드 개발자 이지원입니다.</p>
                <p>현재 집중하는것은  Vue.js 이고, 그리고 관심있는 것은 Three.js , Svelte, Metaverse 입니다. </p>
                <p>#날것의 #스펀지같은상태 #센스탑재</p> 
                        
                <p class="emoji t-6">👀</p> 
                <p>Site: freecodecamp,  techcrunch, ttime, ITWORLD</p>
                <p>Youtube: Traversy Media, Nomad coders,eo, 드림코딩by엘리 </p> 
            </div>
          </v-row>
        </v-col>
<!-- End of 3rd section -->

<!-- 4th section : contact -->
        <v-col cols="12">
          <v-row>
            <div class="fourth" id="contact">
              <h1>CONTACK</h1>    
              <v-btn 
                    v-for="icon in icons" 
                    :key="icon" 
                    class="justify-space-around mt-8 ml-6 mr-6" 
                    icon @click="icon.path"
              >
              <v-icon size="35px" color="#c739ff">{{ icon.name }}</v-icon>
              </v-btn>
              <h2> 👆🏻 </h2>
              <div id="text">
                  <h3>"If you want to know about me then CLICK!!" </h3>
                  <h3>"Grab a cup of Coffee? then CLICK!!"</h3>  
              </div>        
            </div> 
          </v-row>
        </v-col>
<!-- End of 4th section -->       
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

  .app #home {
    background: #ffe600;
    right:0;
    left:0;
    width:100%;
    overflow-x: hidden;
  }
  .v-app{
    width:100%;
    overflow-x: hidden;
  }
  
  .first {
    overflow-x: hidden;
    display:flex;
    width:100%;
    height: 100%;
    .col-6{

    }
     .outline {
      color: rgb(250, 250, 250);
      text-shadow: 2px 2px 0 #c739ff, 2px -2px 0 #c739ff, -2px 2px 0 #c739ff, -2px -2px 0 #c739ff, 2px 0px 0 #c739ff, 0px 2px 0 #c739ff,
      -2px 0px 0 #c739ff, 0px -2px 0 #c739ff;
    }
    .hashtag {
      width: fit-content;
      margin-top: 20px;
      font-size: 20px;
      align-content: center;
      color: rgb(250, 250, 250);
    }
    .top {
    margin-top: 180px;
    }
  }
 

  .second {
    overflow-x: hidden;
    width: 100%;
    text-align: center;
    margin-top:210px;
    color:#010146;
    .pf-box {
      border: 4px dotted #379700;
      border-bottom: 8px solid #00008f;
      _border: 3px dashed #010146;
      border-radius: 20px;
    }
      .pfIcon {
      display: block;
      justify-content:center;
      margin-top: 2px;  
      p{
        _border: 2px solid #000000;
        border-radius: 50px;
      }
      #desc{
        margin: 10px 0 5px 0; 
        h3 {
          margin-bottom: 12px;
        }   
        span{
          margin:0 5px; 
            img{
            height:30px;
            width: 30px;
            }
         }
        }
      }
    .techIcon{
      margin-top:10px;
      .tech_img{
        margin-top: 10px;
        flex-direction: row;
        img{
          height:30px;
          _width:30px;
          margin-left: 6px;
        }
      }       
    }

  }
   
 
  .third {
    overflow-x: hidden;
    width: 100%;
    text-align: center;
    padding: 3rem 3rem;
    color: #030331;
    .emoji{
      font-size: 1.7rem;
    }
    .third h1{
      margin-top: 50px;
      color:#010146;
    }
    .third h3{
      color:#c739ff;
    }
    .third h5{
      color:#c739ff;
    }
  }

 
  .fourth {
    overflow-x: hidden;
    width: 100%;
    text-align: center;
    padding: 3rem 3rem;
    color:#010146;
    h2 {
      margin-top: 30px;
    }
    h3{
      margin-top: 10px;
     }
  }
 
.row.pf{
 right: 0;
 left: 0;
}

.col-3 {
    flex: 0 0 25%;
    max-width: 20%;
}
</style> 

