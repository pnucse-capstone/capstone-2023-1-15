### 1. 프로젝트 소개

VR 환경에서의 사용자 반응 모니터링 툴을 개발하였습니다. 사용자 반응 모니터링을 위해 리얼 센스 카메라를 통해 사용자의 행동 데이터를 녹화 및 리플레이 하며, Unity 환경 상에서 VR 상호작용을 녹화 및 리플레이 합니다. 이를 통해 VR 개발을 용이하게 하는 것이 최종 목적입니다.

### 2. 팀소개

최현호, Unity 환경 녹화 엔진 개발, Unity Test 환경 개발
<br/>
이희근, realSense 카메라를 통한 사용자 행동 녹화, 스켈레톤 데이터 추출 및 유니티 상 표현

### 3. 시스템 구성도

![흐름도](https://github.com/pnucse-capstone/capstone-2023-1-15/assets/38308307/a70735bd-ad5a-464f-bed7-448eeffe9f08)

### 4. 소개 및 시연 영상


### 5. 설치 및 사용법
본 프로젝트는 Unity 2021.3.15.f1 버전을 사용하여 개발하였습니다.
## 1. 레포지토리 클론 (https://github.com/heonhochoi/ReplayEngine)
  해당 레포지토리를 복사합니다.
## 2. Unity 설치
  Unity 2021.3.15.f1 버전을 설치합니다.
## 3. RealSense 파일 설치
  - OpenCV (버전 상관없음)
  https://opencv.org/releases/ <br/>
  - Intel RealSense SDK <br/>
  https://github.com/IntelRealSense/librealsense <br/>
  - numpy, opencv, pyrealsense2 <br/>
  command 창에서 입력 <br/>
  pip install numpy <br/>
  pip install opencv-python <br/>
  pip install pyrealsense2 <br/>
## 4. 장비 연결
  오큘러스 퀘스트 및 리얼센스 카메라를 데스크탑 혹은 노트북에 연결

## 5. 녹화 및 리플레이
  Unity의 각 Object에 MovingObjectRecorder Script 부착<br/>
  Recorder 게임오브젝트의 Recording 체크 후 플레이<br/>
  Recorder 게임오브젝트의 Replaying 체크 후 플레이
  
