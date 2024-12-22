# SafeHaven 팀 프로젝트 소개
 
<img src="https://github.com/user-attachments/assets/9c50e0d2-adb6-4cb4-9805-d8b81fac070f" alt="프로젝트 로고" width="300" height="auto" />

## 목차
- [팀 소개](#팀-소개)
- [프로젝트 개발 이유](#프로젝트-개발-이유)
- [프로젝트 개요](#프로젝트-개요)
- [실행 방법](#실행-방법)
- [실행 영상](#실행-영상)
- [마무리 및 인사](#마무리-및-인사)

---
## 팀 소개

### 팀 이름: **세명 같은 네명**

| 이름   | 역할                   | 별명    | 사진                                                                 |
|--------|------------------------|---------|----------------------------------------------------------------------|
| <div style="text-align: center;">정창민</div> | <div style="text-align: center;">팀장 / 백엔드</div> | <div style="text-align: center;">창미니</div>  | <div style="text-align: center;"><img src="m6hfgq.jpg" width="150" height="auto" /></div>                   |
| <div style="text-align: center;">한성진</div> | <div style="text-align: center;">부팀장 / 백엔드</div> | <div style="text-align: center;">진라면</div>  | <div style="text-align: center;"><img src="crop_Screenshot_20200324-203647_KakaoTalk.jpg" width="150" height="auto" /></div> |
| <div style="text-align: center;">김민진</div> | <div style="text-align: center;">프로그래머 / 프론트엔드</div> | <div style="text-align: center;">지니</div>    | <div style="text-align: center;"><img src="https://github.com/user-attachments/assets/654737eb-956b-42ac-b2a4-9f4d390cf545" width="150" height="auto" /></div> |
| <div style="text-align: center;">권지원</div> | <div style="text-align: center;">엔지니어 / 관리 및 보조</div> | <div style="text-align: center;">잼미니</div>  | <div style="text-align: center;"><img src="Screenshot_20241221_145741_Gallery.jpg" width="150" height="auto" /></div>  |

## 프로젝트 개발 이유

[폭행]을 해결하기 위해 이 프로젝트를 기획하게 되었습니다. 

### 주요 동기:
1. **문제 정의**: 폭력은 개인, 가족, 사회에 여러 가지 부정적인 영향을 미친다. 물리적, 심리적 피해뿐만 아니라, 폭력은 사회적 갈등을 심화시키고, 경제적 비용을 발생시키며, 장기적으로 사람들의 삶의 질을 떨어뜨린다.

2. **목표**: 목표는 폭력을 예방하고, 피해자를 보호하며, 폭력적인 행동이 사회에서 뿌리내리지 않도록 하는 것이다.

### 기술 스택:
- **프론트엔드**: html, css
- **백엔드**: Flask, OpenCV, MediaPipe
---

## 실행 방법

### 1. 환경 설정
1. **프로젝트**
   ```bash
   python --version
   ```
   https://www.anaconda.com/

2. **필요한 패키지 설치**
   ```bash
   pip install opencv-python
   
   pip install mediapipe
   ```
### . 실행 영상
[영상]

---
## 프로젝트 개요

### 프로젝트 이름: **폭력이 없어지는 그날까지**

### 주요 기능(MVP):
- **기능**: 캠에서 사람의 손을 인식하여 설정 좌표값에서 얼마나 빨리 이동하는지에 따라 위협이 뜬다.

### 향후 발전:
- **추가 조건**: 지금은 손만 인식했지만 추가 조건
- 1. 맞을 때 얼굴을 감정인식으로 무서움이나 공포, 슬픔 등의 감정을 인식하도록 한다.
  2. 객체 인식을 활용하여 바운딩 박스 안에 설정 거리 보다 가까워지거나 신체가 닿았을 때.
  3. 


## 마무리 및 인사
지금까지 저희 프로젝트를 지켜봐 주셔서 감사합니다 앞으로도 더 발전하는 세명같은 네명 팀이 되겠습니다 더 고칠부분이나 궁금한 점이 있으시면 말씀해주시면 감사하겠습니다.
