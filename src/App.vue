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
#app { margin:0 auto; _width:750px; min-height:100%; }

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
    .first{
      white-space: inherit;
      word-break: keep-all;
    }
     .first h1{
      font-size: 20px;
    }
    .first MARQUEE {
      font-size: 15px;
      width: 300px;
      height: 25px
    }

    .second{
      text-align: center;
      white-space: inherit;
      word-break: keep-all;
    }
    .second #desc h3{
      font-size: 20px !important;
    }
    .second .pf-box {
      display: table
    }
    .second .pfIcon  p img{
      display: block;
      margin: auto;
    }
  }
  @media(max-width:630px){
    .first{
      flex-direction: column;
      max-width:100%;
      text-align: center;
      position: relative;
    }
    .col .intro-img{position: relative;}
    .col .intro-text{position: absolute;}

    .first .v-img{
      justify-content: center;
      width:380px;
      height: 420px;
      position: relative;
    }
    .v-image{
      max-height:400px;
      height:420px;
      margin-right: 100px;
    }

    .first .top{
      margin-top: 0 !important;
    }
    #intro > div:nth-child(2) > h3 {
      margin-top: 50px;
    }
    
    .first .col-6 {
      flex-wrap:nowrap;
      max-width:100%; 
      position: relative;
    }
   
    #intro > div:nth-child(2) > h3{
  
      margin: 30px 110px 0 0;
    }
    .first h1 {
      font-size: 20px;
      margin: 10px 105px 0 0;
    }
    .first h5 {
      margin: 10px 100px 0 0;
    }
    .first .hashtag{
      margin: 0%;
      left: 0%;
      right: 0%;
      margin-left: 20px;
    }
    .first MARQUEE {   
      _display: table; 
      width: 400px;  
      margin-top: 20px;
      color: #fafafa;
    }
    .second {
      padding-top: 80px;
      margin-top: 0%;
      max-width: 100%;
    }
    .second h1 {
      width: 80px;
      margin-left:95px;
    }
    .second .icon img {
      height: 60px;
    }
    .second .col-3{
      max-width: 70%;
    }
    .second .justify-space-around {
      display: block;
    }
    .v-application .mt-14 {
      margin-left: 68px;
      margin-top: 56px !important;
      max-width: 100%;
    }
    .second .pf-box {
      margin-bottom: 30px;
      width:225px;
    }

    .third {
      margin-right: 80px;
      padding: 0 !important;
    }
    .third h1{
      margin-top: 85px;
    }
    .third p{
      font-size: 15px;
    }
    .fourth{
      margin-right: 80px;
      margin-top: 55px !important;
    }
    .fourth h3 {
      font-size:16px;
    }
  }
  @media(max-width:475px){
    .v-toolbar__content, .v-toolbar__extension {  
      align-items: center;
      display: flex;
      position: relative;
      z-index: 0;
      justify-content: center;
    }
    .v-btn.v-size--default {
      font-size: 0.7rem;
    }
    .first .v-img{
      justify-content: center;
      width:300px;
      height:380px;
    }
    .v-image{
      max-height:400px;
      height:420px;
      margin-right: 50px;
    }
    .first MARQUEE {
      width: 300px;
      margin: 10px;
    }
    .first h3 {
      margin: 0 70px 0 0!important;
    }
    .first h1 {
       margin: 5px 60px 0 0;
    }
    .first .hashtag {
      margin: 0 !important ;
    }
    .second{
      white-space: inherit;
      word-break: keep-all;
      padding-top: 80px !important;
      margin-top: 0% !important;
    }
   .second h1 {
      width: 8px;
      margin-left:57px;
    }
     .second .col-3{
      max-width: 80%;
    }
    .second .pf-box{
      margin-bottom: 20px;
      width: 200px;
    }
    .v-application .mt-14 {
    margin-left: 36px;
    margin-top: 56px !important;
    max-width: 100%;
    }
    .second .pfIcon {
    display: flex;
    justify-content: center;
    margin-top: 2px;
    }
    .second .pfIcon #desc {
    font-size: 14px;
    }
    .second .techIcon{
      display: none;
    }
    .third{
      margin-right: 65px;
    }
     .fourth{
      margin-right: 65px;
    }
  }

  @media(max-width:375px){

    .first .col-6{
      margin: 0 15px;
    }
    .first MARQUEE {
      width: 215px;
    }
    .second{
      display: table;
      white-space: inherit;
      word-break: keep-all;
    }
    .second .col-3{
      max-width: 90%;
    }
    .second .v-application .mt-14 {
      margin-left: 16px;
      max-width: 100%;
    }
    .second h1{
      margin-left: 10px;
    }
    .second .pf-box{
      margin-left: -40px;
    }
    .third{
      margin-right: 50px;
    }
    .fourth {
      margin-right: 50px;
    }
   
  } 
  @media(max-width:346px){
    .first .v-img{
      background-position: top !important;
    }
    .first h3{
    font-size:15px;
    }
    .first .outline{
      display: flex;
      justify-content: center;
    }
    .first h1{
      font-size: 18px;
    }
    .second h1{
      margin-left: 39px;
    }
    .second .pf-box{
      margin-left: -21px;
    }

    .fourt{
      padding: 0;
    }
    .fourth{
      margin-top: 100px;
    }
    .fourth h1{
      margin-left:-16px;
      margin-top: 30px;
    }
  }
  </style>
