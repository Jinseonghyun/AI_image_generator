# Banksy
- 모든 인적 사항이 정체불명인 영국의 아티스트 뱅크시에게 영감을 받아 만들게 된 AI 이미지 생성기
지피티 API를 활용한 AI 이미지 플랫폼 

## 1. 목표와 기능

### 1.1 목표
Banksy 프로젝트는 그림을 그릴 줄 모르거나 다양한 그림에 대한 아이디어가 필요한 사용자가 간편하게 AI를 활용하여 이미지를 생성하고 공유하는 데에 목적이 있습니다. 

### 1.2 기능
- **이미지 생성:** 사용자가 입력한 텍스트 또는 주제를 기반으로 AI를 활용하여 이미지를 생성합니다.
- **이미지 공유:** 생성된 이미지를 손쉽게 다운로드하거나 공유할 수 있습니다.
- **확장 가능성:** 추가적인 AI 모델 및 기능의 통합을 통해 서비스를 확장할 수 있습니다.

### 1.3 팀 구성
<table>
	<tr>
		<th>진성현</th>
	</tr>
 	<tr>
		<td><img src="team.jpg" width="100%"></td>
	</tr>
</table>

## 2. 개발 환경 및 배포 URL

### 2.1 개발 환경
- **Frontend:** HTML, CSS, JavaScript
- **AI 모델:** OpenAI API

### 2.2 배포 URL
- [프로젝트 배포 URL](배포 URL을 입력하세요)

### 2.3 URL 구조(모놀리식)
- [배포 URL]/generate-image
- [배포 URL]/download-image
- [배포 URL]/share-image

### 2.4 URL 구조(마이크로식)
- [generate.image.yourdomain.com]
- [download.image.yourdomain.com]
- [share.image.yourdomain.com]

## 3. 요구사항 명세와 기능 명세
- https://www.mindmeister.com/ 등을 사용하여 모델링 및 요구사항 명세를 시각화 하였습니다.
<img src="logic.png" width="100%">

## 4. 프로젝트 구조와 개발 일정

### 4.1 프로젝트 구조

 ┃ ┣ 📂AI-image-generator  
 ┃ ┣ 📜imdex.html  
 ┃ ┣ 📜draw.js  
 ┃ ┣ 📜style.css 


### 4.1 개발 일정(WBS)
<img src="schedule.png" width="100%">

```mermaid
    title Banksy
    dateFormat YY-MM-DD
    section 기획
        WBS 작성   :2023-02-09, 1d
        주제 선정 위한 자료조사 :2023-02-09, 1d
        UI 구상/수정 :2023-02-10, 1d
        최종 주제 선정과 UI 확정 :2023-02-11, 1d
        챗지피티API IMG 기능 확인 :2023-02-12, 1d
        세부사항 추가 구성 :2023-02-13, 1d
    section 디자인
        디자인 :2023-02-13, 1d
    section FE
        메인   :2023-02-14, 1d
        배경확정  :2023-02-14, 1d
        입력창등록    :2023-02-14, 2d
        구성요소 수정    :2023-02-15, 2d
        기능확인    :2023-02-15, 1d
```

## 5. 역할 분담
개인 프로젝트

- FE : 진성현
- 디자인 : 진성현
## 6. 와이어프레임 / UI / BM

### 6.1 와이어프레임
<img src="UI.png" width="100%">

### 6.2 화면 설계
이미지 결과 나오는 화면 캡쳐
<img src="UI.png" width="100%">

## 7. 데이터베이스 모델링(ERD)
필요시 데이터베이스를 구축하기 위한 ERD를 작성합니다.

## 8. Architecture
프로젝트의 아키텍처를 설명하고 각 구성 요소의 역할을 명시합니다.

## 9. 메인 기능
주요 기능에 대한 상세한 설명을 작성합니다.

## 10. 에러와 에러 해결
API를 연동하여 이미지를 생성하고 UI에 업로드 하는 과정에서 에러가 발생하였는데 내가 준 draw.js에 body 에 설정해주었던 n 과 size의 문제였다. 그래서 UI가 감당할 수 있는 값들로 변경 후 결과값이 잘 출력되는 것을 관찰하였다.

## 11. 개발하며 느낀점
정말 많이 부족하다고 느꼈다. 아이디어나 기획자체에서는 해보고 싶은 것이 정말 많고 여러 기능을 구현하고 싶었는데 막상 주제에 가장 기초적인 이미지를 그려주게 하는 것 부터 구현하는데 무척 애를 먹었다. 요즘은 인공지능이 발달하여 chatGPT라는 실시간으로 정보를 얻을 수 있는 AI가 존재하기에 적극 활용하였지만 이것이 없었다면 내가 과연 이걸 완성할 수 있었을까?? 라는 생각을 정말 많이했다. 이번 계기로 나의 부족함을 한번 더 상기시키는 경험이 되었고 내가 가고자 하는 목표에 가까워 질 수 있도록 더욱 지식을 공부하고 역량을 늘려나가겠다 다짐했다.