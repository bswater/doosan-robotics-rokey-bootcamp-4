# 두산로보틱스 로키부트캠프 4기

2025년 두산로보틱스 ROKEY 부트캠프에서 수행한 협동로봇·자율이동로봇 프로젝트와 실습 코드를 정리한 저장소입니다. 프로젝트별 목표와 이 저장소에서 볼 수 있는 자료를 아래에 모았습니다.

## 프로젝트

| 구분 | 프로젝트 | 구현 내용 | 저장소 자료 |
| --- | --- | --- | --- |
| 협동 1 | 사서 보조 및 독서 지원 로봇 | 책 반출입, 페이지 넘김, 청소를 보조하는 협동로봇 시스템 | 프로젝트 소개 |
| 협동 2 | 편의점 물품 자동 정리 시스템 | 음성 명령과 영상으로 물품을 식별하고, 로봇팔로 집어 정리 | [ROS 2 패키지](./Cooperation2/RF_Robot_Arm) |
| 협동 3 | TurtleBot3 자율주행 및 로봇팔 제어 | TurtleBot3 자율주행, 물품 인식 및 로봇팔 제어 실습 | [실습 자료](./Cooperation3) · [Autorace 코드](./turtlebot3/turtlebot3_autorace) |
| 지능 1 · 중간 | 시각장애인 보조 로봇 | 시각장애인의 이동을 보조하는 로봇 시스템 | 프로젝트 소개 |
| 지능 1 · 최종 | 무인 박물관 시스템 | 복수의 이동로봇을 활용한 박물관 안내 및 순찰 | 프로젝트 소개 |

## 코드 살펴보기

- **편의점 물품 자동 정리** — [음성 처리](./Cooperation2/RF_Robot_Arm/voice_processing), [물체 인식](./Cooperation2/RF_Robot_Arm/object_detection), [ArUco 검출](./Cooperation2/RF_Robot_Arm/aruco_detection), [로봇팔 제어](./Cooperation2/RF_Robot_Arm/robot_control)로 구성되어 있습니다. 패키지의 통합 실행 구성은 [launch 파일](./Cooperation2/RF_Robot_Arm/launch/full_system.launch.py)에서 확인할 수 있습니다.
- **TurtleBot3 주행** — [Autorace 패키지](./turtlebot3/turtlebot3_autorace)와 [협동 3 실습 압축 파일](./Cooperation3)을 확인할 수 있습니다.
- **두산로보틱스 ROS 2 참고 코드** — [DoosanBootcamp3rd](./DoosanBootcamp3rd)에는 로봇 구동, 제어, 메시지, 예제 패키지가 있습니다.
