# bicopter_simulation

### 프로젝트 소개 (Project Introduction)
---

비행안정성 기반 운용시간 증대를 위한 바이콥터 시스템에 관한 연구


(Study on a Bi-Copter System for the Efficiency of Operating Time Based on the Stability of the Flight)

상위 논문을 실험하고 입증하기 위한 방법으로 가제보 시뮬레이션 구축하였음.

(Gazebo simulation was constructed as a method to experiment and verify the thesis).

### 연구방법 (Research method)

1. sim_vehicle.py -v ArduCopter -f JSON --add-param-file=$HOME/ros_ws/src/bicopter_simulation/config/bicopter.param --console --map의 고도화(advancement)
2. gz sim -v4 -r bicopter_runway.sdf의 고도화(advancement)


### 연구기간 (Research period)

2023년 8월 (August 2023) ~ 2024년 8월 (August 2024)

### 멤버 (People)

1. GreenPine-CK
2. SansationHJ

### 주요파일 경로 (File paths)

```
/home/lck/gz_ws/src/bicopter_simulation/models/bicopter
/home/lck/gz_ws/src/bicopter_simulation/models/bicopter_with_ardupilot
/home/lck/gz_ws/src/bicopter_simulation/worlds
/home/lck/ros_ws/src/bicopter_simulation/config
```

### 바이콥터 비행모드 (bicopter flight Mode)

| # | Copter | Plane |
| --- | --- | --- |
|  0 | STABILIZE | MANUAL |
|  1 | ACRO | CIRCLE |
|  2 | ALT_HOLD |STABILIZE |
|  3 | AUTO | TRAINING |
|  4 | GUIDED | ACRO |
|  5 | LOITER | FBWA |
|  6 | RTL | FBWB |
|  7 | CIRCLE | CRUISE |
|  8 |  | AUTOTUNE |
|  9 | LAND |  |
| 10 |  |  |
| 11 | DRIFT | RTL |
| 12 |  |  |
| 13 | SPORT | TAKEOFF |
