<template>
  <v-app id="home" :style="{ background: $vuetify.theme.themes.light.background }">
    <Navbar />

<!-- 1st section : intro page-->
    <v-container fluid align-center>
      <v-row class="mt-14">
      <div class="first" id="intro">
        <v-col cols="6 intro-img" class="intro-img" >
          <v-img src="1.png" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6 intro-text" class="intro-text">
          <h1 class="top" color="#3b41b7">
            어떻게 하면 편리할까 고민하는 
          </h1>
          <div class="outline">
            <h1>Front-end Developer 이지원입니다</h1>
          </div>    
            <div class="hashtag">
              <MARQUEE scrolldelay="100" width="600" height="30" hspace="50" vspace="50" bgColor="#176aff" behavior="scroll" loop="3">
                #html #javascript #scss #vue.js #vuetify #tailwind #github 
              </MARQUEE>
            </div>
         
        </v-col>
      </div>     
<!-- End of 1st section -->

<!-- 2nd section : project -->
      <div class="second " id="project">
        <h1>PROJECTS</h1>
        <v-row class="pf justify-space-around mt-14 flex-{md}-{nowrap}">
          <v-col cols="3" class="pf-box" id="portfolio">           
              <div class="pfIcon">
                <p class="icon">
                  <a href="https://leezy-portfolio.netlify.app" target="blank">
                  <img src="pf.png">
                  </a>
                </p>
                <div id="desc">
                  <h3>Portfolio Web</h3>
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
                 <img src="https://img.icons8.com/windows/32/000000/vuetify.png"/>
              </div>             
            </div>           
          </v-col>
          <v-col cols="3" class="pf-box" id="movie">  
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
          <v-col cols="3" class="pf-box" id="weather">
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
              
        </v-row>
        <v-row class="pf justify-space-around mt-14" md="2">
          <v-col cols="3" class="pf-box" id="covid">           
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
                <img src="tailwind_icon.png" >             

              </div>             
            </div>            
          </v-col>
          <v-col cols="3" class="pf-box" id="squidgame">          
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
                <img src="three_icon.png">
              </div>             
            </div>            
          </v-col>
          <v-col cols="3" class="pf-box" id="renewal">
              <div class="pfIcon">
                <p class="icon">
                  <a href="https://renewal-web.netlify.app/" target="blank">
                  <img src="https://img.icons8.com/external-two-tone-chattapat-/95/000000/external-dance-party-and-celebration-two-tone-chattapat-.png"/>
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
                    <a href="https://github.com/LeezyLazyCrazy/renewal" target="blank">
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
              <div class="about_box">
                <p class="emoji mt-6">👩🏻‍💻</p>
                  <h2>I'm a Flexible Developer</h2>
                  <span class="mt-2">
                    <h4>첫째. 빠알간 Err 줄을 두려워하지 않고 겸허히 인정하고 협력으로 해결해 나아가는 그런 개발자 이지원입니다.</h4>
                    <h4>둘째. IT기술과 문화의 트렌드를 항상 체크하는 개발자 이지원입니다.</h4>                    
                    <h4>셋째. 현재 집중하는것은  Vue.js 그리고 관심있는 것은 Three.js, Svelte, Metaverse 입니다. </h4>
                    <h4>하지만 무엇보다 제가 개발에 있어서 가장 중요시하는 부분은 사용자의 입장에서 쓰기 편리한 맞춤 서비스라고 생각합니다.</h4>
                    <h4>#날것의신입 #스펀지같은상태 #센스탑재</h4>                  
                  </span> 
                  <div class="about_skills ">
                    <p class="emoji t-6">✨</p> 
                    <h2>Skills</h2>
                    <div class="text-center">
                        <v-chip
                        class="ma-2"
                        color="secondary"
                      >
                        Html
                      </v-chip>
                  
                      <v-chip
                        class="ma-2"
                       color="secondary"
                      >
                        CSS
                      </v-chip>
                  
                      <v-chip
                        class="ma-2"
                        color="secondary"
                      >
                        Javascript
                      </v-chip>
                  
                      <v-chip
                        class="ma-2"
                        color="secondary"
                      >
                        vue.js
                      </v-chip>
                  
                      <v-chip
                        class="ma-2"
                        color="secondary"
                      >
                        React
                      </v-chip>
                      
                      <v-chip
                        class="ma-2"
                        color="secondary"
                      >
                        Sass
                      </v-chip>

                      <v-chip
                        class="ma-2"
                        color="secondary"
                      >
                        Vuetify
                      </v-chip>
                    </div>    
                  </div>                   
                    <p class="emoji t-6">👀</p> 
                    <p>References Site: freecodecamp,  techcrunch, ttime, ITWORLD</p>
                    <p>Youtube: Traversy Media, Nomad coders,eo, 드림코딩by엘리 </p>                                        
              </div>
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
              <v-icon size="35px" color="#ffff">{{ icon.name }}</v-icon>
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
    white-space: inherit;
    word-break: keep-all;
    
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
    white-space: inherit;
    word-break: keep-all;

    .outline {
      font-size:20px;
      color: rgb(250, 250, 250);
      text-shadow: 2px 2px 0 #6886C5, 2px -2px 0 #6886C5, -2px 2px 0 #6886C5, -2px -2px 0 #6886C5, 2px 0px 0 #6886C5, 0px 2px 0 #6886C5,
      -2px 0px 0 #6886C5, 0px -2px 0 #6886C5;
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
    color:#3b41b7;
    }
  }
 

  .second {
    -ms-overflow-style: none;
    overflow-x: hidden;
    width: 100%;
    text-align: center;
    margin-top:210px;
    padding: 6em 3em;
    color:#7325ff;
    .second::-webkit-scrollbar{ display:none; }

    .pf-box {
      background-color: #e7e7e7;
      border: 6px dotted #ffbc6d;
      border-bottom: 14px solid #ff6325f5;
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
          color: #3921aa;
          font-size: 30px;
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
    padding: 6rem 10rem;
    color: #7325ff;
    .about_box{
      white-space: inherit;
      text-align: center;
      margin-top: 20px;
      border: 7px dotted #ece3ae;
      border-bottom: 10px solid #ece3ae;
      border-radius: 60px;
      background-color: #46724f47;
      color: #fafafa;
      padding: 0 10px 0 10px;
      word-break: keep-all;
      
    }
    .about_skills {
      margin-bottom: 20px;
    }

    .emoji{
      font-size: 1.7rem;
      margin:16px 0 16px 0;
    }
    .third h1{
      margin-top: 50px;
      color:#010146;
    }
    .third .about_sills{
      width: 72%;
      display: flex;
      flex-direction: column;
      margin: 0 auto;      
    }
  }

 
  .fourth {
    overflow-x: hidden;
    width: 100%;
    text-align: center;
    padding: 3rem 3rem;
    color:#7325ff;
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

