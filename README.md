# TASK1 - Web Page 만들기 READ ME

---

  ## 1. 개괄

    HTML과 CSS, Java Script에 대하여 배운 내용을 이용해서 프론트 엔드에 대한 이해를 심화하기 위한 웹페이지 생성 프로젝트입니다.

---

  ## 2. 구성 기간
  
    - 2024.08.20(화) ~ 2024.08.28(목)

---

  ## 3. 개발자
  
     -정승원(JSW0721) : HTML 웹페이지 구성, CSS 스타일 구성,  JS script 작성.

---

  ## 4. 개발 환경

     -IDE : InteliJ
     
     -서비스 배포 환경 : Github pages
     
     -배포 URL : <https://jsw0721.github.io/TASK1/TASK1-Webpage/TASK1.htm>

     -배포 레포지토리 : <https://github.com/JSW0721/TASK1>

---

  ## 5. 구현, 반영 기능

  ### 5.1 미디어 쿼리

      미디어 쿼리를 이용하여 MAX WIDTH : 400PX 미만의 화면에서는 모바일용 화면으로 보여주도록 CSS 구성



  ### 5.2 이메일 주소 검증 기능 구현

      이메일 형식이 아닌 빈 공간이나 불특정 String이 입력되면 Warning 팝업창 구현.


  ### 5.3 모달창 구현
      JavaScript를 이용하여 Modal을 구현하는 방법 실습.
      JavaScript를 통해 CSS를 변경, 수정하도록 작동하게 만드는 방법 실습. 

---

  ## 6. 프로젝트 구조

┗📂TASK1-Webpage

  ┣ 📂.idea
  
  ┃ ┣ 📜.gitignore
  
  ┃ ┣ 📜misc.html
  
  ┃ ┣ 📜modules.html
  
  ┃ ┣ 📜vcs.html
  
  ┃ ┗ 📜workspace.html
  
  ┣ 📂css
  
  ┃ ┗ 📜style.css
  
  ┣ 📂img
  
  ┣ ┗ 📜 imges
  
  ┣ 📂js
  
  ┃  ┣ 📂vendor
  
  ┃  ┃  ┗📜.gitkeep
  
  ┃  ┗ 📜 app.js
  
  ┣ 📜.editorconfig
  
  ┣ 📜.gitatributes
  
  ┣ 📜.gitognore
  
  ┣ 📜 404.html
  
  ┣ 📜 favicon.ico
  
  ┣ 📜 icon.png
  
  ┣ 📜 icon.html
  
  ┣ 📜 icon.index
  
  ┣ 📜 license.txt
  
  ┣ 📜 package.txt
  
  ┣ 📜 robots.txt
  
  ┣ 📜 site.webmanifest
  
  ┣ 📜 TASK1.html  // 메인 화면
  
  ┣ 📜 TASK1_script.js  //메인 자바스크립트 문서
  
  ┣ 📜 TASK1_sytle.css  //메인 스타일 문서
  
  ┣ 📜 webpack.common
  
  ┣ 📜 webpack.config.dev
  
  ┗ 📜 webpack.config.prod

  ---

  ## 7. 프로젝트 작성 후 감상

    프론트 엔드에서 웹페이지를 만들어 보면서 디자인 요소들 적용하는것도 생각보다 쉽지 않다는걸 느꼈습니다.

    아울러, 백엔드에서 쿼리문을 거쳐서 가져와야하는 정보들이 어떤 과정을 거쳐서 사용자들에게 보여질지 유추해 볼 수 있는 경험이었습니다. 

    하루 늦었다는 압박감에 피그마에 있는 내용들을 있는 그대로 위치를 강제적으로 고정해주며 개발했더니 모바일 화면 구현 단계에서

    html문서를 처음부터 다시 작성해야 하는 대참사를 겪었어서 급하더라도 개발 요구사항을 확인하면서 계획을 세우는게 필요하단걸 배웠습니다. 

