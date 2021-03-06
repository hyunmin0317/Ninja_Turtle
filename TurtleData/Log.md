## Turtle Data

`Ninja_turtle에 필요한 데이터를 웹캠을 통해 수집하여 csv 파일로 만들기`

<br>

### Mediapipe Pose Landmark

<img src="https://github.com/hyunmin0317/Ninja_Turtle/blob/master/TurtleData/result/landmark.PNG?raw=true" alt="landmark" style="zoom:33%;" />

* 거북목 판별에 필요한 landmark: NOSE, RIGHT_EAR, LEFT_EAR, RIGHT_SHOULDER, LEFT_SHOULDER

<br>

### 기본 요구사항(ver 1)

+ lanmark의 좌표 데이터 접근
+ 직선과 세 점 사이의 거리 계산
  + 직선: RIGHT_SHOULDER, LEFT_SHOULDER로 이루어진 직선
  + 점: NOSE, RIGHT_EAR, LEFT_EAR
+ 직선과 세 점 사이의 거리 출력
+ 세 점 사이의 거리 데이터와 가중치를 csv 파일로 저장

<br>

### Log

+ ver 1.0 - 판별에 필요한 5개 lanmark의 좌표 데이터 접근 후 직선과 세 점 사이의 거리를 계산하여 출력 (최현민) - 2021.05.02

+ ver 1.1 - 세 점 사이의 거리 데이터를 'turtledata.csv' 파일로 저장 (최현민, 임혜지) - 2021.05.03

  ![turtledata](https://github.com/hyunmin0317/Ninja_Turtle/blob/master/TurtleData/result/turtledata.PNG?raw=true)

+ ver 2.0

  + 세 점 사이의 거리 데이터의 가중치를 'turtleweight.csv' 파일로 저장 (최현민) - 2021.05.03

    ![turtleweight](https://github.com/hyunmin0317/Ninja_Turtle/blob/master/TurtleData/result/turtleweight.PNG?raw=true)

  + 좋은 자세와 좋지 않은 자세의 데이터를 수집하기 위해 영상 상단에 현재 수행할 자세 종류를 글과 다른 색으로 표시 (최현민) - 2021.05.03

    ![result](https://github.com/hyunmin0317/Ninja_Turtle/blob/master/TurtleData/result/result(ver.2.0).PNG?raw=true)
  
  

