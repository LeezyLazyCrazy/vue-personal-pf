<template>
  <v-app>
    <div class="wrap">
      <v-main>
        <router-view/>
      </v-main>
    </div>    
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
 <style>
  /* 반응형 최대크기 */
#app { margin:0 auto; _width:750px; min-height:100%; positon:relative;  }

  /* 여백제거 + 드래그방지 */
body{ padding:0; margin:0; -ms-user-select: none; -moz-user-select: none; -khtml-user-select: none; -webkit-user-select: none; user-select: none; }

  /* 반응형 시작 */
  @media(max-width:830px){
    #app{ width:100%; border-left:0; border-right:0;}
    .first h1{
      font-size: 25px;
    }
    .first MARQUEE {
    width:350px; height: 25px; justify-content: center; align-items: center;
    }
  }


  @media(max-width:735px){
     .first h1{
      font-size: 20px;
    }
    .first MARQUEE {
      font-size: 15px;
      width: 300px;
      height: 25px
    }
  }


  @media(max-width:630px){
    .first{
      flex-direction: column;
      width:100%;
      text-align: center;
    }
    .first .v-img{
      justify-content: center;
      width:380px;
      height: 420px;
    }
    .v-image{
      max-height:400px;
      height:420px;
    }

    .first .top{
      margin-top:0%;
    }
    #intro > div:nth-child(2) > h3 {
      margin-top: 50px;
    }
    
    .first .col-6 {
      flex-wrap:nowrap;
      max-width:100%; 
    }
    .first .top {
      margin-top: 180px;
    }
    .first .hashtag{
      margin: 0%;
      left: 0%;
      right: 0%;
    }
    .first MARQUEE {   
      display: table;   
      margin-top: 20px;
      color: #fafafa;
    }
    .second {
      padding-top: 80px;
      margin-top: 0%;
    }
    .second .icon img {
      height: 60px;
    }
    .second .col-3{
      max-width: 50%;
    }
    .second .justify-space-around {
      display: block;
    }
    .v-application .mt-14 {
      margin-left: 90px;
      margin-top: 56px !important;
    }

    .second .pf-box {
      margin-bottom: 30px;

    }
  }
  </style>
