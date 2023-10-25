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
                <h3>Certificate & Award</h3>
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
                <h3>Contact</h3>
                
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
        <p>2022년부터 백엔드 개발자를 희망하고 준비하고 있습니다. 원하는 서비스를 상상하는 것 뿐만 아니라 실제로 만들어 낼 수 있다는 점에서 프로그래밍에 매력을 느끼게 되었습니다.</p>
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
              <h1>개발 환경</h1>
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
          수상 및 자격증, 프로젝트 제외 활동 내역입니다. 아르바이트, 교육 등 다양한 경험을 하기 위해 노력하고 있습니다.
        </div>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>코드잇 강의 수강</h2>
            <p>2021-06~2021-09</p>
          </div>
          <div class="ex-list">
            <li>프로그래밍에 대한 지식이 많이 부족했던 저학년 때 기본 지식을 배우고자 신청하고  수료하였습니다.</li>
            <li>프로그램잉에 대한 기본 이해, 프로그래밍 언어 학습 등을 할 수 있었습니다.</li>
          </div>
        </div>
        <hr>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>4차 산업 연구회</h2>
            <p>2021-10~2022-12</p>
          </div>
          <div class="ex-list">
            <li>명지전문대학 정보통신공학과 학과 동아리에 들어가 대외활동, 공모전, 프로젝트 등 다양한 활동을 해보았습니다.</li>
            <li>동아리 내에서 서류 및 백엔드 개발을 담당하였고, 어떻게 해야 효율적인 팀 활동을 할 수 있는지에 대해 배울 수 있었습니다.</li>
          </div>
        </div>
        <hr>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>한이음 ICT 멘토링</h2>
            <p>2022-03~2022-09</p>
          </div>
          <div class="ex-list">
            <li>'안전한 근로 환경을 보장하는 스마트 안전모'라는 주제로 ICT 멘토링에 참여하였습니다.</li>
            <li>하드웨어 제어 및 Express릃 활용한 백엔드 개발을 경험해 볼 수 있었습니다.</li>
          </div>
        </div>
        <hr>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>전공 튜터링</h2>
            <p>2022-03~2023-06, 2023-03~2023-06</p>
          </div>
          <div class="ex-list">
            <li>객체지향언어실습, 자료구조 과목에 대한 튜터로 전공 튜터링을 진행했습니다.</li>
            <li>객체지향에 대한 학습 및 JAVA 언어에 대한 이해도 향상에 많은 도움이 되었습니다.</li>
          </div>
        </div>
        <hr>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>Alpha mini 교재 번역 아르바이트</h2>
            <p>2022-09</p>
          </div>
          <div class="ex-list">
            <li>인공지능 교육자료 알파미니 로봇의 강의 학습 교재 번역 아르바이트를 했습니다.</li>
            <li>새로운 분야에 대한 학습을 해볼 수 있는 기회였습니다.</li>
          </div>
        </div>
        <hr>
        <div class="ex-list-grid">
          <div class="ex-list">
            <h2>학습법 특강</h2>
            <p>2022-12</p>
          </div>
          <div class="ex-list">
            <li>'JAVA 언어에 대한 기본 이해'라는 주제로 학과 학습법 특강을 진행했습니다.</li>
            <li>약 1시간 정도의 강의 준비였지만, 해당 과젱어서 Java 언어에 대한 이해도를 높일 수 있었습니다.</li>
          </div>
        </div>
        <hr>

      </div>

      

      <div class="modal-background" v-if="showModal" @click="closeModal"></div>
      <div>

        <div class="modal" v-if="showModal">
          <!-- 모달 내용 -->
          <div class="modal-content">
            <div class="project-infor">
              <h2>자동 출입 시스템</h2>
              <p>진행 기간 : 2022-04~2022-0</p>
              <p class="cate">카테고리 : H/W</p>
              <a href="https://github.com/0uizi0/automatic-access-system">github</a>
            </div>
            <div class="project-grid">
              <div class="project-image">
                <v-img class="my-pic" src='@/assets/access.png'></v-img>
              </div>
              <div class="project-des">
                <p>[딥러닝을 활용한 자동 출입 시스템 제작]</p>
                <li>Open CV를 이용한 딥러닝 모델 개발을 활용해 관리자 접근 허용</li>
                <li>아두이노 우노와 라즈베리 파이 간의 시리얼 통신</li>
                <li>아두이노 우노와 연결된 지문인식센서를 통해 관리자 접근 허용</li>
                <li>아두이노 우노와 연결된 RFID 센서를 통해 관리자를 제외한 일반 사용자의 접근 허용</li>

                <li>접근이 허용될 경우 LED 점등 및 LCD 문구 출력, 서보모터를 통해 출입문 열림</li>
            <li>관리자와 일반 사용자의 접근 경로를 달리해 보안 강화</li>
              </div>
            </div><br>

            <div class="project-my">
              <h3>담당한 부분 : 하드웨어 제어 및 이미지 딥러닝</h3>
              <p>python을 사용한 라즈베리파이 및 모듈 제어, Open CV를 활용한 이미지 딥러닝 담당</p>
              
            </div>
            <div class="project-skill">
              <h3>기술 스택</h3>
              <li>Arduion IDE</li>
              <li>Python 3.7.9</li>
              <li>Raspberry pi 4</li>
            </div>

            <div class="project-feel">
              <h3>배운점</h3>
              <p>프로젝트를 진행하며 하드웨어에 대한 전반적인 이해력 향상 및 딥러닝 방식에 대한 지식을 학습할 수 있었음</p>
            </div>

            <!-- 모달 내용 추가 -->

            <button @click="closeModal">닫기</button>
          </div>
        </div>

        <div class="modal-background" v-if="showModal2" @click="closeModal2"></div>

        <div class="modal" v-if="showModal2">
          <!-- 모달 내용 -->
          <div class="modal-content">
            <div class="project-infor">
              <h2>동아리 홍보 페이지</h2>
              <p>진행 기간 : 2022-08~2022-09</p>
              <p class="cate">카테고리 : 웹 사이트</p>
              <a href="https://xd.adobe.com/view/a0b75416-116b-4fe6-8144-84aefec9c212-f5e4/screen/3d716e28-7636-44e9-9f9a-d5e7236710df">디자인</a>
            </div>
            <div class="project-grid">
              <div class="project-image">
                <v-img class="my-pic" src='@/assets/4this.png'></v-img>
              </div>
              <div class="project-des">
                <p>[동아리 신입 부원 모집 사이트]</p>
                <p>동아리 홍보 시 제대로 정리를 보여줄 방법이 마땅치 않아 웹 사이트 기획하게 됨</p>
                <p>동아리의 수상/활동 일정/활동 인원/목표 등과 같은 동아리 홍보 내용 제공</p>
                <p>동아리 신청 방식에 대한 공지 및 유의사항 전달</p>
              </div>
            </div>
            <div class="project-my">
              <h3>담당한 부분 : 기획 및 디자인</h3>
              <p>사이트의 전반적인 기획 구성 및 디자인</p>
            </div>
            <div class="project-skill">
              <h3>사용 툴</h3>
              <li>Adobe XD</li>

            </div>

            <div class="project-feel">
              <h3>배운점</h3>
              <p>평소에는 개발로만 프로젝트에 참여하던 중, 동아리 홍보가 필요한 상황에서 프로젝트 기획을 경험해 보고 싶어 시작하게 되었음. 기획 및 디자인이 어떤 절차로 이루어지는지, 개발 시 기획자와 어떻게 소통해야할지 등에 대해 배울 수 있었음</p>
            </div>

            <!-- 모달 내용 추가 -->

            <button @click="closeModal2">닫기</button>
          </div>
        </div>

        <div class="modal-background" v-if="showModal3" @click="closeModal3"></div>

        <div class="modal" v-if="showModal3">
          <!-- 모달 내용 -->
          <div class="modal-content">
            <div class="project-infor">
              <h2>스마트팜</h2>
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

            <button @click="closeModal3">닫기</button>
          </div>
        </div>

        <div class="modal-background" v-if="showModal4" @click="closeModal4"></div>

        <div class="modal" v-if="showModal4">
          <!-- 모달 내용 -->
          <div class="modal-content">
            <div class="project-infor">
              <h2>학원관리시스템</h2>
              <p>진행 기간 : 2023-10~2023-1012</p>
              <p class="cate">웹 사이트</p>
              <a href="">github</a>
            </div>
            <div class="project-grid">
              <div class="project-image">
                <v-img class="my-pic" src='@/assets/service.png'></v-img>
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

            <button @click="closeModal4">닫기</button>
          </div>
        </div>


        <div class="modal-background" v-if="showModal5" @click="closeModal5"></div>

        <div class="modal" v-if="showModal5">
          <!-- 모달 내용 -->
          <div class="modal-content">
            <div class="project-infor">
              <h2>DevForDev</h2>
              <p>진행 기간 : 2023-10~2023-1012</p>
              <p class="cate">웹 사이트</p>
              <a href="https://github.com/bboggo/devfordev">github</a>
            </div>
            <div class="project-grid">
              <div class="project-image">
                <v-img class="my-pic" src='@/assets/service.png'></v-img>
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

            <button @click="closeModal5">닫기</button>
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
            <v-img class="my-pic" src='@/assets/access.png' width="100%" height="300px"></v-img>
            <div class="port-text">
              <h3>자동 출입 시스템</h3>
              <p>2022-04~2022-06</p>
              <p class="cate">H/W</p>
            </div>

          </div>


          <div class="port"
         data-aos="fade-up"
         data-aos-duration="4000"
         @mouseenter="activatePort"
         @mouseleave="deactivatePort"
         @click="openModal2">
            <v-img class="my-pic" src='@/assets/4this.png' height="300px"></v-img>
            <div class="port-text">
              <h3>동아리 홍보 페이지</h3>
              <p>2022-08~2022-09</p>
              <p class="cate">웹 사이트</p>
            </div>

          </div>


          <div class="port"
         data-aos="fade-up"
         data-aos-duration="4000"
         @mouseenter="activatePort"
         @mouseleave="deactivatePort"
         @click="openModal3">
            <v-img class="my-pic" src='@/assets/node.png' height="300px"></v-img>
            <div class="port-text">
              <h3>스마트팜</h3>
              <p>2022-09~2022-12</p>
              <p class="cate">웹 사이트</p>
            </div>

          </div>



          <div class="port"
         data-aos="fade-up"
         data-aos-duration="4000"
         @mouseenter="activatePort"
         @mouseleave="deactivatePort"
         @click="openModal4">
            <v-img class="my-pic" src='@/assets/node.png' height="300px"></v-img>
            <div class="port-text">
              <h3>학원관리 시스템</h3>
              <p>2023-08~2023-11</p>
              <p class="cate">웹 사이트</p>
            </div>

          </div>



          <div class="port"
         data-aos="fade-up"
         data-aos-duration="4000"
         @mouseenter="activatePort"
         @mouseleave="deactivatePort"
         @click="openModal5">
            <v-img class="my-pic" src='@/assets/service.png' height="300px"></v-img>
            <div class="port-text">
              <h3>DevForDev</h3>
              <p>2023-03~07</p>
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
    showModal2: false,
    showModal3: false,
    showModal4: false,
    showModal5: false,
    isActivated: false,
    isFlipped: false, 
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

    openModal2() {
      this.showModal2 = true; // 모달 창 열기
    },
    closeModal2() {
      this.showModal2 = false; // 모달 창 닫기
    },

    openModal3() {
      this.showModal3 = true; // 모달 창 열기
    },
    closeModal3() {
      this.showModal3 = false; // 모달 창 닫기
    },

    openModal4() {
      this.showModal4 = true; // 모달 창 열기
    },
    closeModal4() {
      this.showModal4 = false; // 모달 창 닫기
    },

    openModal5() {
      this.showModal5 = true; // 모달 창 열기
    },
    closeModal5() {
      this.showModal5 = false; // 모달 창 닫기
    },

    activatePort() {
      this.isActivated = true;
    },
    deactivatePort() {
      this.isActivated = false;
    },
    flipCard() {
      this.isFlipped = true;
    },
    unflipCard() {
      this.isFlipped = false;
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
  width: 150px;
   margin-left: auto;
   margin-right: auto;
  font-size: 20px;
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
  padding: 20px;
  width: 100%;
}


.port-text {
  margin-top: 10px;
  font-weight: 400;
}
.port-text h3 {
  font-size: 20px;
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
  height: 750px;
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

.modal button {
  float: right;
  
}
.modal-content {
  /* 모달 내용 스타일 설정 */
}

.project-grid {
  display: grid;
  grid-template-columns: 1fr 1.5fr;
  gap: 20px;
}



</style>