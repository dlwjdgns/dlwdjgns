# 👨‍💻 이정훈 | Embedded & Robotics Software Engineer

> **"하드웨어 제약을 소프트웨어 최적화로 극복하는 엔지니어"**  
> 단순 부품 조립을 넘어, 명확한 요구사항 분석(SRS)과 인터페이스 설계(ICD)를 바탕으로 안정적인 펌웨어 및 ROS2 기반 분산 시스템을 개발합니다.

- 📧 **Email:** junghoonlee.dev00@gmail.com
- 🔗 **GitHub:** [github.com/dlwjdgns](https://github.com/dlwjdgns)

---

## ⚙️ Tech Stacks

| Classification | Technologies |
| :--- | :--- |
| **Languages** | C, C++, Python |
| **Embedded & MCU** | STM32 (F103/F411/H523), ATmega328P, FreeRTOS, STM32CubeMX |
| **Robotics & OS** | Ubuntu 24.04 LTS, ROS2 (Humble/Jazzy), Gazebo, Nav2 |
| **Vision & Edge AI** | TensorFlow, OpenCV, YOLO, LiteRT (INT8 Quantization), MediaPipe |
| **Protocols & Tools** | CAN, UART, I2C, SPI, Git/GitHub, CMake |

---

## 🚀 Key Projects

### 1. VIP Wearable (시각장애인 보행 보조 시스템)
- **Period:** 2026.08 (제24회 임베디드 SW 경진대회)
- **Role:** 팀장 (시스템 아키텍처 설계, 비전 AI 경량화 및 펌웨어 통합)
- **Stack:** Raspberry Pi 5, STM32F411RE, Ubuntu 24.04, Python, C
- **Key Features:**
  - **Edge AI Semantic Segmentation:** YOLO26n-sem 모델을 최적화하여 4개 주요 클래스(0: 도로, 1: 인도, 2: 횡단보도, 3: 점자블록) 실시간 인식
  - **INT8 양자화 최적화:** LiteRT INT8 Quantization을 적용하여 mIoU 방어 및 온디바이스 추론 지연 최소화
  - **센서 융합 및 인터럽트 펌웨어:** STM32F411RE 기반 초음파 센서(HC-SR04) 데이터 처리, 낙상 감지 알고리즘 구현 및 Bluetooth 통신 전송
  - **보행 내비게이션:** TMAP API 연동을 통한 보행자 맞춤형 경로 가이드 통합

---

### 2. Pinky (자율 순찰 및 정밀 도킹 AMR)
- **Period:** 2026.08
- **Role:** 1인 개발 (ROS2 내비게이션 및 제어 로직 전담)
- **Stack:** ROS2 (Jazzy), Gazebo Ignition, RViz2, Python
- **Key Features:**
  - **Nav2 자율주행 파이프라인:** AMCL 기반 위치 추정 및 복수 웨이포인트 순환 순찰 액션 서버 구현
  - **PID 제어 기반 후진 정밀 도킹:** 글로벌 경로 플래너 한계를 극복하기 위해 충전 스테이션 진입 시 자체 개발한 후진 정밀 도킹 PID 알고리즘 적용
  - **3D 시뮬레이션 모델링:** URDF/Xacro를 활용한 로봇 kinematics 및 LiDAR/Camera 센서 모델링, SDF 가제보 환경 구축

---

### 3. CAN-Bus 기반 다중 노드 RC 카 시스템
- **Period:** 2026.07 ~ 2026.08
- **Role:** 메인 ECU 펌웨어 개발
- **Stack:** STM32, C, CAN Protocol
- **Key Features:**
  - **CAN 아키텍처 및 ICD 설계:** 메인 ECU, 디스플레이 클러스터, RFID 컨트롤러 노드 간 충돌 없는 통신을 위한 CAN 프레임 규격 수립
  - **속도 제어 정밀화:** STM32 32비트 타이머 Input Capture 모드를 통한 엔코더 펄스 캡처 및 주행 속도 오차 최소화
  - **Safe-Fail 긴급 제동:** 초음파 센서 임계치 도달 시 외부 인터럽트를 발생시켜 모터 출력을 차단하는 비상 제동 로직 탑재

---

## 📚 Education & Certifications

- **학력:** 전자공학 및 임베디드 시스템 전공 (GPA: 4.15 / 4.5)
- **자격증:**
  - 정보처리기사
  - 정보통신기술자 경력수첩 (초급)
- **교육:** 대한상공회의소 서울기술교육센터 AI융합 로봇 소프트웨어 개발자 과정 (수료 예정)

- ### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dlwjdgns&theme=tokyonight" alt="GitHub Streak" />
</p>
