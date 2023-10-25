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
                <h3>My Information</h3>
                <p>이름 | 김민지</p>
                <p>생년월일 : 2000.08.19</p>
                <p>학력</p>
                <p>2023.02 | 명지전문대학 정보통신공학과 졸업</p>
                <p>2023.03 ~ | 명지전문대학 정보통신공학과 전공심화 재학중</p>
              </div>
            </v-carousel-item>

            <v-carousel-item>
              <div class="infor-text1">
                <h3>Certificate</h3>
                <p>2022.04 | 리눅스 마스터 2급 | 한국정보통신인력개발센터</p>
                <p>2022.09 | 정보처리산업기사 | 한국산업인력공단</p>
                <p>2023.09 | 정보처리기사 | 한국산업인력공단</p>
                <br>

                <p>2022.11 | 명지전문대학 정보통신공학과 동상</p>

                <p>2022.12 | 명지전문대학 캡스톤디자인대회 동상</p>
              </div>
            </v-carousel-item>

            <v-carousel-item>
              <div class="infor-text1">
                <h3>Contact & Award</h3>
                
                <p>E-mail: kmt0819@naver.com</p>
                <p>Phone: 010-3958-3589</p>
                <a href="https://github.com/bboggo">github</a>

                <a href="https://velog.io/@bboggo">blog</a>

                <a href="https://purring-pasta-b76.notion.site/Kim-Min-Ji-567d94a278a04158a36e58ea5dfb1be1?pvs=4">notion</a>

              </div>
            </v-carousel-item>
          </v-carousel>
          </div>

        </div>
      </div>

      <div class="text">
        <p>⭐ 백엔드 개발자가 되고 싶은 김민지입니다. ⭐</p>
        <p>2022년부터 백엔드 개발자를 희망하고 준비하고 있습니다. 원하는 서비스를 상상하는 것 뿐만 아니라 실제로 만들어 낼 수 있다는 점에서 프로그래밍에 매력을 느끼고 되었습니다.</p>
        <p>프로젝트와 이론에 대한 공부를 함께하며 노력해 나아가고 있습니다:) </p> 
      </div>

      <div class="skiils">
        <div class="title">
          <h1>Skills</h1>
        </div>
        <div class="skill-grid">
          <div class="backend">
            <div class="name">
              <h1>백엔드 프레임워크</h1>
            </div>
            <div class="skill-list">
              <ul>
                <li>Spring Boot</li>
                <li>Express</li>
              </ul>
            </div>
          </div>
          <div class="database">
            <div class="name">
              <h1>데이터베이스</h1>
            </div>
            <div class="skill-list">
              <ul>
                <li>MySQL</li>
                <li>Oracle</li>
              </ul>
            </div>
          </div>
          <div class="environ">
            <div class="name">
              <h1>개발 환경 및 생산성</h1>
            </div>
            <div class="skill-list">
              <ul>
                <li>Gradle</li>
                <li>Lombok</li>
                <li>Tomcat</li>
              </ul>

            </div>
          </div>

          <div class="cloud">
            <div class="name">
              <h1>클라우드 및 통신</h1>
            </div>
            <div class="skill-list">
              <ul>
                <li>AWS RDS</li>
                <li>AWS EC2</li>
                <li>AWS S3</li> 
              </ul>
            </div>
          </div>

          <div class="git">
            <div class="name">
              <h1>배포 및 형상 관리</h1>
            </div>
            <div class="skill-list">
              <ul>
                <li>Git</li>
                <li>GitHub</li>
              </ul>
            </div>
          </div>

          <div class="frontend">
            <div class="name">
              <h1>프론트엔드</h1>
            </div>
            <div class="skill-list">
              <ul>
                <li>Vus.js</li>
                <li>Html5</li>
                <li>JavaScript</li>
                <li>CSS</li>
              </ul>

            </div>
          </div>
        </div>
        <!-- <div class="skill-image">
          <v-img class="my-pic" src='@/assets/node.png' width="100px"></v-img>
          <v-img class="my-pic" src='@/assets/spring.png' width="100px"></v-img>
          <v-img class="my-pic" src='@/assets/node.png' width="100px"></v-img>
          <v-img class="my-pic" src='@/assets/spring.png' width="100px"></v-img>
          <v-img class="my-pic" src='@/assets/node.png' width="100px"></v-img>
          <v-img class="my-pic" src='@/assets/spring.png' width="100px"></v-img>
        </div> -->
      </div>
      

      <div class="Experience">
        <div class="title">
          <h1>Experience</h1>
        </div>
        <div class="ex-text">
          수상 및 자격증, 프로젝트 제외 활동 내역입니다. 아르바이트, 교육 등 다양한 경험을 해보았습니다.
        </div>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>코드잇 강의 수강</h2>
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
            <h2>4차 산업 연구회 동아리</h2>
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
            <h2>한이음 ICT 멘토링</h2>
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
            <h2>전공 튜터링</h2>
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
            <h2>학습법 특강</h2>
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
            <h2>Alpha mini 교재 번역 아르바이트</h2>
            <p>2023-10-21~</p>
          </div>
          <div class="ex-list">
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다.</li>
            <li>아르바이트, 교육 등 다양한 경험을 해보았습니다. 이 과정에서 많은 것을 배울 수 있었고 많은 성장을 할 수 있었습니다.</li>
          </div>
        </div>
      </div>

      

      <div class="modal-background" v-if="showModal" @click="closeModal"></div>
      <div>
        <!-- 모달 창 -->
        <div class="modal" v-if="showModal">
          <!-- 모달 내용 -->
          <div class="modal-content">
            <div class="project-infor">
              <h2>학원 관리 시스템</h2>
              <p>진행 기간 : 2023-10~2023-1012</p>
              <p class="cate">웹 사이트</p>
              <a href="">github</a>
            </div>
            <div class="project-grid">
              <div class="project-image">
                <v-img class="my-pic" src='@/assets/smartfarm.png'></v-img>
              </div>
              <div class="project-des">
                어떤 프로젝트인지 기획에 대해서 설명
              </div>
            </div>
            <div class="project-my">
              <h3>내가 담당한 부분 : 백엔드</h3>
              
            </div>
            <div class="project-skill">
              <h3>기술 스택</h3>
              <li>Spring Boot</li>
              <li>Spring Boot</li>
              <li>Spring Boot</li>
            </div>

            <div class="project-feel">
              <h3>느낀점</h3>
              <p>어떤 점을 느꼈는지 아주 자세하게 쓰려고함ㅁ. 진짜 자세하게 학원관리 시스템을 만들면서 무슨 감정을 느꼈고 그래봤자 안좋은 감정이지 뭐</p>
            </div>

            <!-- 모달 내용 추가 -->

            <button @click="closeModal">닫기</button>
          </div>
        </div>
      </div>

      <div class="portfolio">
        <div class="title">
          <h1>Portfolio</h1>
        </div>
        <div class="portfolio-grid">

          <div class="port"
         data-aos="fade-up"
         data-aos-duration="4000"
         @mouseenter="activatePort"
         @mouseleave="deactivatePort"
         @click="openModal">
            <v-img class="my-pic" src='@/assets/node.png'></v-img>
            <div class="port-text">
              <h3>학원관리 시스템</h3>
              <p>2023-10-21~</p>
              <p class="cate">웹 사이트</p>
            </div>

          </div>

          <div class="port" ddata-aos="fade-up" data-aos-duration="4000">
            <v-img class="my-pic" src='@/assets/smartfarm.png'></v-img>
            <div class="port-text">
              <h3>학원관리 시스템</h3>
              <p>2023-10-21~</p>
              <p class="cate">웹 사이트</p>
            </div>

          </div>

          <div class="port" data-aos="fade-up" data-duration="2000">
            <v-img class="port-img" src='@/assets/node.png'></v-img>
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
    showModal: false,
    isActivated: false
  }),

  mounted() {
    this.typeText('백엔드 개발자', 'subtitle')
      .then(() => {
        this.subtitle = '백엔드 개발자';
        return this.typeText('김민지의 포트폴리오입니다.', 'name');
      })
      .then(() => {
        this.name = '김민지의 포트폴리오입니다.';
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
    openModal() {
      this.showModal = true; // 모달 창 열기
    },
    closeModal() {
      this.showModal = false; // 모달 창 닫기
    },
    activatePort() {
      this.isActivated = true;
    },
    deactivatePort() {
      this.isActivated = false;
    },
  }
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

.main h1 {
  font-size: 40px;
}

.main h3 {
  font-size: 25px;
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
  padding: 70px 100px;
  height: 90%;
  background-color: rgb(255, 251, 242);
}

.infor-text1 h3 {
  font-size: 30px;
  color: rgb(222, 173, 77);
  margin-bottom: 50px;
}

.infor-text1 p {
  margin-bottom: 10px;
  font-size: 18px;
  font-weight: 500;
  padding-bottom: 10px;
}

.infor-text1 a {
  background-color: black;
  color: white;
  border-radius: 10px;
  padding: 10px;
  margin-right: 10px;
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

.text p {
  font-weight: 600;
}

.skill-grid {
  margin: 0 200px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 50px;
  text-align: center;
}

.skill-grid h1 {
  font-size: 25px;
  margin-bottom: 20px;
  font-weight: 600;
  letter-spacing: 5px;
}

.backend, .environ, .skill-grid .git {
  background-color: rgb(244, 216, 159);
  padding: 30px 50px;
}



.frontend, .database, .cloud {
  background-color: #F5F5F5;
  padding: 30px 50px;
}

.skill-image {
  margin: 50px 200px;
}

.skill-image .my-pic {
  float: left;
  margin: 0 20px 100px 20px;
}

ul {
  list-style-position: outside;
  list-style-type: circle;
  text-align: center;
}
ul li {
  width: 100px;
   margin-left: auto;
   margin-right: auto;

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
  gap: 100px;
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

.modal-background {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.7); /* 검정색 배경 및 투명도 조절 */
  z-index: 999; /* 다른 요소 위에 표시되도록 z-index 설정 */
}

.modal {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: #fff;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
  z-index: 1000; /* 뒷 배경보다 위에 표시 */
  width: 700px;
  height: 700px;
}

.modal .cate {
  margin-bottom: 10px;

}
.modal a {
  background-color: black;
  color: white;
  padding: 10px;
  margin: 20px 0;
  border-radius: 10px;
}

.modal img {
  margin-top: 20px;
}

.modal h3 {
  margin: 10px 0;
}
.modal-content {
  /* 모달 내용 스타일 설정 */
}

.project-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
}

</style>