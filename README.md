# bicopter_simulation

### 프로젝트 소개 (Project Introduction)
---

비행안정성 기반 운용시간 증대를 위한 바이콥터 시스템에 관한 연구


(Study on a Bi-Copter System for the Efficiency of Operating Time Based on the Stability of the Flight)

상위 논문을 실험하고 입증하기 위한 방법으로 가제보 시뮬레이션 구축하였음.

(Gazebo simulation was constructed as a method to experiment and verify the thesis).

### 연구방법 (Research method)

1. `sim_vehicle.py -v ArduCopter -f BiCopter --model JSON` 의 고도화
2. `gz sim -v4 -r bicopter_runway.sdf` 의 고도화

### 연구기간 (Research period)

2023년 8월 (August 2023)

/home/lck/gz_ws/src/ardupilot_gazebo/worlds

### 멤버 (People)

1. GreenPine-CK
2. SansationHJ

### 주요파일 경로 (File paths)

```bash
/home/lck/gz_ws/src/ardupilot_gazebo/models/bicopter_with_standoffs

/home/lck/gz_ws/src/ardupilot_gazebo/models/bicopter_with_ardupilot

/home/lck/gz_ws/src/ardupilot_gazebo/worlds/bicopter_runway.sdf

bicopter_runway.sdf > bicopter_with_ardupilot > bicopter_with_standoffs
```
