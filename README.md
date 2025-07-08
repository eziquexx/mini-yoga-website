# 🧘‍♀️🔁🌐 요가원 반응형 웹사이트 리뉴얼
> 실존하는 요가 스튜디오의 웹사이트를 벤치마킹하여 Redesign을 하였습니다.<br>
> 그리고 반응형으로도 제작하여 사용자가 다양한 방식으로 접근을 할 수 있도록 하였습니다.
```
- 개발 기간: 2024-06-25 ~ 2024-08-04
- 목적: React를 이해하고 개인이 가볍게 사용할 목적으로 React를 사용하여 To-do List를 제작하였습니다.
```
---

## 🧩 구현 기능
<table>
  <thead>
    <tr>
      <th>기능</th>
      <th>설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>원페이지 반응형</td>
      <td>하나의 페이지에 PC, 태블릿, 모방리 너비에 맞춤 반응형 개발</td>
    </tr>
    <tr>
      <td>메뉴 고정</td>
      <td>상단에 menu를 고정하여 스크롤 다운을 해도 상시 보임</td>
    </tr>
    <tr>
      <td>토글 기능</td>
      <td>768px 이하에서 메뉴 버튼이 토글 형태로 바뀐다. 스케쥴 섹션을 접었다 폈다 할 수 있다.</td>
    </tr>
    <tr>
      <td>세션 이동</td>
      <td>메뉴를 클릭하면 해당 섹션으로 부드럽게 이동함</td>
    </tr>
    <tr>
      <td>이미지 모달창</td>
      <td>실내 사진을 클릭하면 이미지 팝업창으로 보다 이미지를 크게 볼 수 있음.<br> 그리고 모달창이 실행됐을 경우 스크롤 기능을 막음.</td>
    </tr>
  </tbody>
</table>

---

## 🛠 사용 기술 스택
- HTML5
- CSS3
- JavaScript
- Tools: VS Code, Git & GitHub, GitHub Pages

---

## 🎬 배포 & 데모
🚀 [배포 사이트 바로가기](https://eziquexx.github.io/mini-yoga-website/) - GitHub Pages로 배포

---

## 📘 프로젝트 상세 기록 (블로그)
👉 [포스팅 보러가기](https://dev-jelee.tistory.com/entry/mini-project-Yoga-Responsive-Website-Re-design) - 티스토리에 올린 포스트

---

## 📁 디렉토리 구조

```
📂 YOGA/
├── index.html         // 메인 웹페이지
├── img/               // 정적 이미지 모음
├── js/                // 동적 기능 자바스크립트
│   ├── modal.js 
│   ├── moveSection.js 
│   ├── scheduleToggleBtn.js 
│   ├── toggleBtn.js 
│   └── topBtn.js
├── style/              // 스타일(CSS)+미디어쿼리
│   ├── about.css
│   ├── classContent.css
│   ├── classType.css
│   ├── components.css
│   ├── contact.css
│   ├── faq.css
│   ├── footer.css
│   ├── history.css
│   ├── home.css
│   ├── modal.css
│   ├── navBar.css
│   ├── reset.css
│   ├── schedule.css
│   ├── studioGallery.css
│   └── topBtn.css
```

---

## :eyes: 개발 참고 자료
- 메뉴 클릭하면 각 섹션으로 이동, top 버튼 클릭하면 상단으로 이동
  - [mozilla-scrollTo](https://developer.mozilla.org/en-US/docs/Web/API/Element/scrollTo)
  - [mozilla-offsetTop](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/offsetTop)
- 모달창, 마우스 스크롤과 모바일 스크롤 방지
  - [w3scholl-modal](https://www.w3schools.com/howto/howto_css_modal_images.asp)
  - [stackoverflow-disabling mouse scrolling](https://stackoverflow.com/questions/7915882/disabling-mouse-scrolling)
  - [mozilla-overflow](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow)
  - [codepen-Disable scroll on Desktop and Mobile](https://codepen.io/wesleypimentel/pen/KpgXJW)
  - [stackoverflow-Disable scrolling in all mobile devices](https://stackoverflow.com/questions/10592411/disable-scrolling-in-all-mobile-devices)

---

