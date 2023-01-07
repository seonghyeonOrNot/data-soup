<template>

  <nav class="navi">
    <a>logo</a>
    <a v-for="a in navis" :key="a"> {{a}} </a>
  </nav>

  <nav class="navi2">
   <div><a> home</a></div>
    <div></div>
    <div class="navi2-right">
      <a>menu1</a>
      <a>menu2</a>
      <a>menu3</a>
    </div>

  </nav>

  <div class="subject">
   <div class="subject-left">
      <p>
        Delicious Data <span class="subject-sub"> data - soup</span>
        
      </p>
      <p>
         데이터쟁이는 국내 최소, 최고 AI해커톤 플랫폽입니다. 기업에는 AI 솔루션과 전문인력 채용의 기회를 개인에겐 경쟁하며 성장하는 소통의 장을 제공합니다.
         데이터쟁이를 접하는 모든 분들께는 최고의 파트너가 되겠습니다. 
         
      </p>

      <p>진행소식을 팔로우 하고 싶은 분들은 클릭해주세요</p> 
      <button class="email-btn">click me click me</button>
   </div>

   <div class="subject-right">
    <a href="#" > <img src="./assets/drkb.png" alt="img"></a>
   </div>
  </div>

 

  <div class="hide">
    <a href="#" > <img src="./assets/item1.png" style="width:200px" alt="img"></a>
    <a href="#" > <img src="./assets/item2.png" alt="img"></a>
    <a href="#" > <img src="./assets/item3.png" style="width:200px" alt="img"></a>
<!-- <a href="#"><img src="./assets/hn1-1.png" alt="hn1-1" style="width:300px"></a> -->

  </div>

  <!-- <div class="icon">
    <a href="#" > <img src="./assets/item1.png" style="width:200px" alt="img"></a>
    <a href="#" > <img src="./assets/item2.png" alt="img"></a>
    <a href="#" > <img src="./assets/item3.png" style="width:200px" alt="img"></a>
    </div> -->

    <div class="body-one">
    <p>DATASET.</p>
    <p>data soup에서 데이터 분석 할 데이터를 찾고 데이터 분석 경험을 통해 데이터 역량을 높이고 포트폴리오로써 사용이 가능</p>
    <a href="#"> <img src="./assets/hn1.png" alt="hn1"></a>
    
   </div>

   <div class="body-second">
    <p>PlayData.</p>
    <p>매일 걷기와 같은 일상 데이터 뿐만 아니라 DATASET의 데이터를 통해  발견한 유의미한 패턴을 분석한 결과물을 공유하고 재미있는 인사이트를 나눠보세요.</p>
    <div class="icon">
    <a href="#" > <img src="./assets/item1.png" style="width:200px" alt="img"></a>
    <a href="#" > <img src="./assets/item2.png" alt="img"></a>
    <a href="#" > <img src="./assets/item3.png" style="width:200px" alt="img"></a>
    </div>
   </div>

   <div class="body-third">
    <p>myCODE.</p>
    <p>자주쓰는 코드는 저장해두고 필요할 때마다 꺼내쓰기 편하게</p>
    <a href="#"> <img src="./assets/hm2.png" alt="hn1"></a>
   </div>


    <div class="subject-middle">
      <p>데이터를 다루고 싶은 주니어</p>
      <p>데이터를 얻을 수 없는 주니어</p>
      <p>어떻게 포트폴리오를 만들어야할지 모르겠는 신입/취준생</p>
      <p>데이터에 친화적이지 않은 지금 회사</p>
      
    </div>

    <div class="card">
      <div>
        <a href="#"><img src="./assets/19.png" alt="tennine" style="width:150px;"></a>
        <span>dddddddddddd</span>
        
      </div>
      <div> 
        <a href="#"><img src="./assets/9.png" alt="nine" style="width:150px;"></a>
        
        </div>
      <div> 
        <a href="#"><img src="./assets/2.png" alt="two" style="width:150px;"></a>
        
        </div>
    </div>

  

  <p>안녕하세요. 서로의 성장을 돕는 회사내 작은 회사, Ambro 입니다.</p>

  <table class="table-view">
    <tr>
      <td>
        회차
      </td>
      <td>
        날짜
      </td>
      <td>
        설명
      </td>
    </tr>
    <tr>
      <td>
        ddddd
      </td>
      <td>
        ddddd
      </td>
      <td>
        ddddd
      </td>
    </tr>
  </table>
</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      navis : ['home', 'about', 'shop', 'my'],
    }
  },
  methods : {
    
  },
  components: {
    
  }
}
</script>

<style>
body{
  margin: 0;
  background: #e5eef9;
}

div{
  box-sizing: border-box;
}

.hide{
  width: 100%;
  height: 500px;
  background: #04162b;
  margin-top: 130px;
}

.email-btn{
  padding: 15px;
  border-radius: 30px;
  border: 0;
  background: #f6dff5;
  color:black;
  font-size: 20px;

}
.body-one :nth-of-type(1){
  color: rgb(9, 6, 94);
  font-weight: 900;
  font-size: 50px;
  margin-bottom: 0;
  padding: 0;
}
.body-second :nth-of-type(1){
  color: rgb(9, 6, 94);
  font-weight: 900;
  font-size: 50px;
  margin-bottom: 0;
  padding: 0;
}
.body-third :nth-of-type(1){
  color: rgb(9, 6, 94);
  font-weight: 900;
  font-size: 50px;
  margin-bottom: 0;
  padding: 0;
}

.subject-middle{
  width: 700px;
  background: pick;
  border: 1px solid black;
  margin: 10px;
  padding: 10px;
}

.subject-middle p {
  color: red;
  
}

.subject{
  width: 700px;
  height: 400px;
  margin: auto;
  display: flex;
}

.subject-left{
  width: 80%;
  text-align: left;
  font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}


.subject-sub{
  /* font-size: 80px; */
  font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  
}

.subject-left p:nth-child(1){
  font-size: 70px;
  font-weight: 900;
  margin-top: 20px;
  /* border: 1px solid red; */
}
.subject-left p:nth-child(2){
  font-size: 20px;
  font-weight: 200;
  /* border: 1px solid red; */
}

.subject-right{
  width:20%;
  margin: auto;
}

.card{
  width: 100%;
  height: 300px;
  background: #2c3e50;
  display: flex;
  
}

.card div{
  width: 200px;
  height: 200px;
  /* background: wheat; */
  margin-right: 20px;
  margin: auto;
  border: 1px solid black;
}

.icon{
  
  width: 100%;
  margin: auto;
  margin-top: 50px;
  height: 300px;
}

.icon img{
  width: 300px;
  /* padding-right: 30px; */
  padding-left: 30px;
}


/* .subject-{
  width: 500px;
  text-align: left;
}

.subject p:nth-child(1){
  font-size: 60px;
  font-weight: 900;
} */

table{
  width: 80%;
  border: 1px solid rgb(215, 213, 213);
  margin: auto;
  
}

table tr:nth-child(1){
  background: rgb(189, 189, 187);
}



.navi2{
  padding: 10px;
  width:100%;
  background: #1f2328;
  display: flex;
}
.navi2 div:nth-child(1){
  width: 10%;
  text-align: left;
}
.navi2 div:nth-child(2){
  width: 70%;
}
.navi2 div:nth-child(3){
  width: 20%;
  text-align: right;
  padding-right: 10px;
}
.navi2 a {
  color: white;
  padding-right: 10px;
}

img{
  width: 500px;
}

.navi{
  padding: 10px;
  width:100%;
  background: #2c3e50;
}

.navi a {
  color: white;
  padding: 10px;
}

.navi a:nth-child(1) {
  color: rgb(209, 11, 84);
  font-weight: 900;
  
  
}





#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top:0;
}
</style>
