# SmartDrug - 스마트한 복약관리 솔루션

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pytorch-EE4C2C?style=flat-square&logo=Pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/ScikitLearn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/GoogleCloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
</p>

> 복용중이던 의약품의 주의사항과 복용알림을 스마트하게 알려드립니다!
<br>

 ## 💡 Motivation of this project
  보건복지부는 2012년 11월 15일부터 소정의 등록 조건을 만족한다면, 약국과 병원 이 외의 판매처에서 ‘안전상비의약품’을 판매할 수 있도록 약사법을 개정하였습니다. 이에 따라 소비자는 일반의약품에 쉽게 접근하며, 약국이 문을 닫는 공휴일과 심야 시간대에도 의약품을 구입할 수 있게 되어 불편을 해소하게 되었습니다.  
이렇게 약사법이 개정됨에 따라 ‘안전상비의약품’을 구매하는 소비자는 약물의 유효성분 마다 주의점과 부작용을 제대로 설명 들을 수 없습니다. 따라서 전문가의 조언 없이 본인의 판 단하에 의약품을 선택해 복용하는 것은 소비자에게 의약품의 오남용, 그로 인한 부작용 등 의 위험이 있을 수 있습니다.  
본 프로젝트에서는 이런 경우를 대비할 수 있도록 의약품의 사진을 찍어 Application이나 반응형 웹 환경에 업로드를 하면 전문가가 아닌 소비자도 의약품의 유효성분과 주의사항 그리고 병용금기 성분 같은 상세정보를 한눈에 확인할 수 있도록 하는 시스템을 개발하는 과정을 담고 있습니다.  

 
<br>

## 📑 Features of this project
 ### ⚙ It Provides:
* 의약품 이미지와 정보를 [NIH](https://www.nlm.nih.gov/) 와 [공공데이터](https://www.data.go.kr/) 에서 받아 [Xception](https://arxiv.org/abs/1610.02357) 모델을 이용하여 학습하였습니다.
* 의약품 사진을 통해 의약품의 상세정보를 확인할 수 있습니다.
* 모바일 앱을 통해 등록된 의약품의 병용금기와 주의사항을 확인할 수 있습니다.

<br>


## 🛠 Technology stacks

### Mobile Client
- Android Studio(Java)
- Figma for design

### Back-End Server
- Python
- Pytorch
- Scikit-learn
- OpenCV
- Tesseract OCR
- Flask

### Web Front-End
- JQuery
- PHP
- NodeJS

<br>

## 🧑‍💻 Project Members
 
<div align="center">
  <table align="center">
    <tr align="center">
      <td align="center"><img src="https://avatars.githubusercontent.com/u/6503979?v=4" width="80"></td>
      <td align="center"><img src="https://avatars.githubusercontent.com/u/113992906?v=4" width="80"></td>
      <td align="center"><img src="https://avatars.githubusercontent.com/u/114410976?v=4" width="80"></td>
      <td align="center"><img src="https://avatars.githubusercontent.com/u/114422867?v=4" width="80"></td>
    </tr>
    <tr align="center">
      <td align="center"><a href="https://github.com/bsy0317">배서연</a></td>
      <td align="center"><a href="https://github.com/Jinwoo53">김진우</a></td>
      <td align="center"><a href="https://github.com/matzzip">최윤철</a></td>
      <td align="center"><a href="https://github.com/nahyeonseo">나현서</a></td>
    </tr>
     <tr align="center">
       <td align="center"><p><i>Back-End<br>Front-End<br>Mobile Client<br>Web<br>Design<br>Documentation</i></p></td>
       <td align="center" colspan="4"><p><i>Documentation</i></p></td>
     </tr>
  </table> 
</div>
 
 <br>
 
 ## 🧾 README.md Reference
 [oss-talkative](https://github.com/oss-talkative/.github) 저장소에서 README.md를 참고하여 수정하였습니다.
