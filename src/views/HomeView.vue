<template>
  <div>
    <nav>

      <div class="header">

        <div class="menu1" @click="scrollToSection('aboutme')">
          About Me
        </div>
        <div class="menu1" @click="scrollToSection('skiils')">
          Skills
        </div>
        <div class="menu1" @click="scrollToSection('Experience')">
          Experience
        </div>
        <div class="menu1" @click="scrollToSection('portfolio')">
          Portfolio
        </div>
      </div>
    </nav>

    <div class="container">
      <div class="main">
        <h3>{{ subtitle }}</h3>
      <h1>{{ name }}</h1>
      </div>

      <div class="aboutme">
          <h1>About Me</h1>
        </div>
      <div class="infor" data-aos="fade-down" data-duration="2000">

        <div class="aboutme-grid">
          <div class="my-image">
            <v-img class="my-pic" src='@/assets/photo.jpg'></v-img>
          </div>
          <div class="about-me-right">
            <v-carousel height="500" hide-delimiters progress="primary">
            <v-carousel-item>
              <div class="infor-text1">
                <h3>자기소개</h3>
                <p>이름 : 김민지</p>
                <p>생년월일 : 2000.08.19</p>
                <p>학력 : 명지전문대학 정보통신공학과 졸업</p>
                <p> : 명지전문대학 정보통신공학과 졸업</p>
              </div>
            </v-carousel-item>

            <v-carousel-item>
              <div class="infor-text1">
                <h3>자기소개2</h3>
                <p>이름 : 김민지</p>
                <p>생년월일 : 2000.08.19</p>
                <p>학력 : 명지전문대학 정보통신공학과 졸업</p>
                <p> : 명지전문대학 정보통신공학과 졸업</p>
              </div>
            </v-carousel-item>

            <v-carousel-item>
              <div class="infor-text1">
                <h3>Contact</h3>
                <p>이름 : 김민지</p>
                <p>생년월일 : 2000.08.19</p>
                <p>학력 : 명지전문대학 정보통신공학과 졸업</p>
                <p> : 명지전문대학 정보통신공학과 졸업</p>
              </div>
            </v-carousel-item>
          </v-carousel>
          </div>

        </div>
      </div>

      <div class="text">
        <p>⭐ 내가 왜 개발자를 하고 싶었는지</p>
        <p>⭐ 나에 대한 소개입니다.</p>
        <p>⭐ 나에 대한 소개입니다.</p> 
      </div>

      <div class="skiils">
        <div class="title">
          <h1>Skills</h1>
        </div>
        <div class="skill-grid">
          <div class="backend">
            <div class="name">
              <h1>BackEnd</h1>
            </div>
            <div class="skill-list">
              <li>Spring Boot</li>
              <li>MySQL</li>
              <li>Spring Boot</li>
              <li>MySQL</li>
            </div>
          </div>
          <div class="frontend">
            <div class="name">
              <h1>FrontEnd</h1>
            </div>
            <div class="skill-list">
              <li>Spring Boot</li>
              <li>MySQL</li>
              <li>Spring Boot</li>
              <li>MySQL</li>
            </div>
          </div>
          <div class="etc">
            <div class="name">
              <h1>Etc</h1>
            </div>
            <div class="skill-list">
              <li>Spring Boot</li>
              <li>MySQL</li>
              <li>Spring Boot</li>
              <li>MySQL</li>
            </div>
          </div>
        </div>
        <div class="skill-image">
          <v-img class="my-pic" src='@/assets/node.png' width="100px"></v-img>
          <v-img class="my-pic" src='@/assets/spring.png' width="100px"></v-img>
          <v-img class="my-pic" src='@/assets/node.png' width="100px"></v-img>
          <v-img class="my-pic" src='@/assets/spring.png' width="100px"></v-img>
          <v-img class="my-pic" src='@/assets/node.png' width="100px"></v-img>
          <v-img class="my-pic" src='@/assets/spring.png' width="100px"></v-img>
        </div>
      </div>
      

      <div class="Experience">
        <div class="title">
          <h1>Experience</h1>
        </div>
        <div class="ex-text">
          아르바이트, 교육 등 다양한 경험을 해보았습니다.
        </div>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>Alpha mini 아르바이트</h2>
            <p>2023-10-21~</p>
          </div>
          <div class="ex-list">
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다.</li>
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다.</li>
          </div>
        </div>
        <hr>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>Alpha mini 아르바이트</h2>
            <p>2023-10-21~</p>
          </div>
          <div class="ex-list">
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다. 이것이 얼마나 소중한 기회였는지 저는</li>
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다.</li>
          </div>
        </div>
        <hr>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>Alpha mini 아르바이트</h2>
            <p>2023-10-21~</p>
          </div>
          <div class="ex-list">
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다.</li>
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다.</li>
          </div>
        </div>
        <hr>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>Alpha mini 아르바이트</h2>
            <p>2023-10-21~</p>
          </div>
          <div class="ex-list">
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다.</li>
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다.</li>
          </div>
        </div>
        <hr>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>Alpha mini 아르바이트</h2>
            <p>2023-10-21~</p>
          </div>
          <div class="ex-list">
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다.</li>
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다.</li>
          </div>
        </div>
      </div>


      <div class="portfolio">
        <div class="title">
          <h1>Portfolio</h1>
        </div>
        <div class="portfolio-grid">

          <div class="port" data-aos="fade-up" data-aos-duration="4000">
            <v-img class="my-pic" src='@/assets/node.png'></v-img>
            <div class="port-text">
              <h3>학원관리 시스템</h3>
              <p>2023-10-21~</p>
              <p class="cate">웹 사이트</p>
            </div>

          </div>

          <div class="port" ddata-aos="fade-up" data-aos-duration="4000">
            <v-img class="my-pic" src='@/assets/node.png'></v-img>
            <div class="port-text">
              <h3>학원관리 시스템</h3>
              <p>2023-10-21~</p>
              <p class="cate">웹 사이트</p>
            </div>

          </div>

          <div class="port" data-aos="fade-up" data-duration="2000">
            <v-img class="my-pic" src='@/assets/node.png'></v-img>
            <div class="port-text">
              <h3>학원관리 시스템</h3>
              <p>2023-10-21~</p>
              <p class="cate">웹 사이트</p>
            </div>

          </div>

          <div class="port" data-aos="fade-up" data-duration="2000">
            <v-img class="my-pic" src='@/assets/node.png'></v-img>
            <div class="port-text">
              <h3>학원관리 시스템</h3>
              <p>2023-10-21~</p>
              <p class="cate">웹 사이트</p>
            </div>

          </div>
        </div>
      </div>
    </div>

    <footer>
      <p>김민지 - 졸업 프로젝트 중간고사 포트폴리오</p>
      <p>© 2023 Kim Min Ji, All Rights Reserved.</p>
    </footer>
    
  </div>
</template>

<script>
export default {
  name: 'App',

  data: () => ({
    subtitle: '',
    name: '',
  }),

  mounted() {
    this.typeText('노력하고 뭐시기하는 개발자', 'subtitle')
      .then(() => {
        this.subtitle = '노력하고 뭐시기하는 개발자';
        return this.typeText('김민지입니다.', 'name');
      })
      .then(() => {
        this.name = '김민지입니다.';
      });
  },

  methods: {
    typeText(text, property) {
      return new Promise((resolve) => {
        let index = 0;
        this[property] = '';

        const type = () => {
          if (index < text.length) {
            this[property] += text.charAt(index);
            index++;
            setTimeout(type, 100);
          } else {
            resolve();
          }
        };

        type();
      });
    },
    scrollToSection(section) {
      // 해당 섹션의 DOM 요소를 선택
      const element = document.querySelector(`.${section}`);
      if (element) {
        // 선택한 요소로 스크롤
        element.scrollIntoView({ behavior: 'smooth' });
      }
    },
  },
};

</script>

<style>

.header {
  display: flex;
  margin: 30px 200px;

  
}

.menu1:hover {
  color: rgb(242, 188, 80);

}

.menu1 {
  font-size: 20px;
  font-weight: 500;
  
}

.header div {
  margin-right: 100px;
}



.main {
  clear: right;
  background-color: rgb(244, 216, 159);
  width: 100%;
  text-align: center;
  padding: 350px 0;
  height: 800px;
}

.container {
  margin: 0 auto;
}

.infor {
  margin: 50px 200px 150px 280px;
}




.aboutme {
  margin: 100px 200px;
}

.aboutme-grid {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 100px;
}

.my-image .my-pic {
  box-shadow: -80px 80px rgb(255, 243, 219);
}

.infor-text1 {
  padding: 100px 150px;
  height: 100%;
  background-color: rgb(255, 251, 242);
}

.infor-text1 h3 {
  font-size: 30px;
  color: rgb(48, 48, 48);
  margin-bottom: 70px;
}

.infor-text1 p {
  margin-bottom: 10px;
  font-size: 20px;
}

.title {
  font-size: 20px;
  text-align: center;
  margin: 80px 0;
  letter-spacing: 8px;
  text-decoration-line : underline;
  text-decoration-color : #F5F5F5;
  text-decoration-thickness : 3px;
  font-weight: 400;
  clear: left;
  
}


.text {
  margin: 0 200px;
  padding: 100px;
  text-align: center;
  background-color: rgb(244, 216, 159);

}

.skill-grid {
  margin: 0 200px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 50px;
  text-align: center;
}

.skill-grid h1 {
  margin-bottom: 20px;
  font-weight: 500;
  letter-spacing: 5px;
}

.backend, .etc {
  background-color: rgb(244, 216, 159);
  padding: 20px 50px;
}



.frontend {
  background-color: #F5F5F5;
  padding: 20px 50px;
}

.skill-image {
  margin: 50px 200px;
}

.skill-image .my-pic {
  float: left;
  margin: 0 20px 100px 20px;

}

.Experience {
  margin: 0 200px;
}

.ex-list-grid {
  display: grid;
  gap: 100px;
  grid-template-columns: 1fr 5fr;
}

.ex-list {
  margin: 50px 0;
}

.ex-list li {
  margin-bottom: 15px;
}



.activity {
  padding: 100px;
}

.stack {
  padding: 100px;
}

.portfolio {
  margin: 0 200px;
  
}

.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 150px;
}

.portfolio-grid .port {
  margin-top: 50px;
}

img {
  transition: transform 0.3s;
}

img:hover {
  transform: scale(1.1);
}

.port {
  box-shadow: 5px 5px 5px 5px rgb(235, 235, 235);
}
.port-text {
  padding: 10px;
  font-weight: 400;
}
.port-text h3 {
  font-size: 30px;
}
.port .cate {
  background-color: rgb(244, 216, 159);
  color: white;
  padding: 10px;
  width: 100px;
}
.port .width {
  width: 100px;
}
footer {
  padding: 20px;
  background-color: rgb(244, 216, 159);
  text-align: center;
  margin-top: 100px;
}

</style>