<template>
  <div>
    <nav>
      <div class="header">

      </div>
    </nav>
    <div class="container">
      <div class="main">
        <h3>노력하고 뭐시기하는 개발자</h3>
        <h1>김민지입니다.</h1>
      </div>

      <div class="infor">
        <div class="infor-left-right">
          <div class="infor-left">
            <h1>김민지</h1>
            <h3>백엔드 개발자</h3>
            <h3>contact : 010-3958-3589</h3>
            <h3>Email : kmt0819@naver.com</h3>

          </div>
          
          <div class="infor-right">
            <v-img class="my-pic" src='@/assets/pen.png' width="300px"></v-img>
          </div>
        </div>


        <div class="infor-link">
          <span class="github">
            <a href="">깃허브</a>
          </span>
          <span class="blog">
            <a href="">블로그</a>
          </span>
          <span class="notion">
            <a href="">노션</a>
          </span>
        </div>
      </div>

      <div class="about-me">
        <div class="title">
          <h1>⭐ About Me</h1>
        </div>
        <p>⭐ 나에 대한 소개입니다.</p>
        <p>⭐ 나에 대한 소개입니다.</p>
        <p>⭐ 나에 대한 소개입니다.</p> 
      </div>

      <div class="education">
        <div class="title">
          <h1>Education</h1>
        </div>
      </div>

      <div class="activity">
        <div class="title">
          <h1>Activity</h1>
        </div>
      </div>

      <div class="portfolio">
        <div class="title">
          <h1>Portfolio</h1>
        </div>
        <div class="portfolio-grid">
          <div class="port">
            <v-img class="my-pic" src='@/assets/pen.png'></v-img>
            <h3>포트폴리오1</h3>
          </div>

          <div class="port">
            <v-img class="my-pic" src='@/assets/pen.png'></v-img>
            <h3>포트폴리오1</h3>
          </div>

          <div class="port">
            <v-img class="my-pic" src='@/assets/pen.png'></v-img>
            <h3>포트폴리오1</h3>
          </div>

          <div class="port">
            <v-img class="my-pic" src='@/assets/pen.png'></v-img>
            <h3>포트폴리오1</h3>
          </div>

          <div class="port">
            <v-img class="my-pic" src='@/assets/pen.png'></v-img>
            <h3>포트폴리오1</h3>
          </div>

          <div class="port">
            <v-img class="my-pic" src='@/assets/pen.png'></v-img>
            <h3>포트폴리오1</h3>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

</script>

<style>
.main {
  background-color: rgb(244, 216, 159);
  width: 100%;

  text-align: center;
  padding: 200px 0;
}

.container {
  background-color: aliceblue;
  margin: 0 auto;
  padding: 0 200px;
}

.infor-left-right {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}

.infor-left {
  padding: 100px;
  text-align: center;
}

.infor-left h1 {
  font-size: 60px;
  margin: 30px 0;
}

.infor-left h3 {
  font-size: 20px;
  margin: 20px 0;
}

.infor-right {
 
  padding: 100px; 
  margin: 0 auto;
}

.infor-right .my-pic {
  border-radius: 150px 0px 150px 150px;
}

.infor-link {
  padding: 100px;
}

.about-me {
  padding: 100px;
  text-align: center;
}



.infor-link span{
  background-color: rgb(66, 142, 170);
  color: white;
  padding: 20px;
  margin: 20px;
  border-radius: 10px;

}

.education {
  padding: 100px;
}

.activity {
  padding: 100px;
}

.portfolio {
  padding: 100px;
}

.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 50px;
}

.portfolio-grid .port {
  margin-top: 50px;
}

</style>