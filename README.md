# todoList

<img width="400"  src="https://user-images.githubusercontent.com/47317129/103032589-c3afdb80-45a3-11eb-9f78-ca577127f29c.PNG" style="display: block" >
## Inspiration

순수 HTML, CSS, JavaScript, MySQL로만 코딩하다가 Node.js, MongoDB를 공부할 목적으로 만든 간단한 앱입니다.

## What it does

해야할 일을 추가하고 완료했을 경우에 체크하면 리스트에서 사라지는 어플리케이션입니다. MongoDB와 연동해두었기 때문에 추가, 삭제가 DB에 반영되어 페이지를 새로고침하여도 데이터가 남아있습니다. 모든 리스트를 삭제할 경우 디폴트 3가지(샤워하기, 운동하기, 꾸미기)가 자동으로 추가되도록 하였습니다.

## How I built it

프론트엔드는 EJS로, 백엔드 서버는 Express를 사용하였으며 Mongoose를 이용하여 MongoDB에 데이터를 저장하였습니다.

## Accomplishments that I'am proud of

이 때는 프리랜서 프론트엔드 개발자로 근무하고 있었는데 현재에 안주하지 않고 새로운 기술을 배우려고 주말에 시간을 할애한 점입니다.

## What I learned

Node.js를 쓰기위해 npm의 세계에 처음으로 발을 들였는데,
세상에 많은 유용하고 흥미로운 라이브러리들이 많다는 것을 알았고 이를 잘 활용하여 앞으로 만들 프로젝트의 완성도를 높여야겠다고 생각했습니다.
<br>
또한 라우팅 개념을 처음 알게 되었습니다. 기존에는 모든 로직이 사용자에게 노출이 되었는데(난독화 하지 않을 경우) 이 부분을 보완할 수 있게 되었습니다.

## What's next for this application

- 회원가입/로그인
- 데드라인 정하기
- 데드라인날에 브라우저 알림 보내기

## Built With

- HTML/CSS
- Node.js
- EJS
- Express
- MongoDB

# Try it out!

<a href="http://49.247.208.236:3000/" target="_blank">이곳에서 직접 프로젝트를 확인해보세요.</a>
