# 안녕하세요, 조혜은입니다

**MCU 펌웨어로 센서를 읽고 모터를 움직이고, 비전·앱과 연결해 하나의 시스템으로 만드는 일을 합니다.**

- 🔧 관심 분야: 임베디드 펌웨어, 센서·액추에이터 제어, 비전-제어 연동 시스템
- 🎓 【학교】 전기전자공학 【학년】
- 📫 【이메일】

---

## Projects

### 🦯 [Navis — AI 기반 시각장애인 반자율 보행 보조 시스템](https://github.com/samareosa-cloud/2026ESWContest_free_JOJOLEEHAN)
`2026 임베디드SW경진대회` · **팀장** · ESP32 · Raspberry Pi · Flutter

카메라로 횡단보도·신호등을 인식하고, 모터 조향 토크로 사용자의 보행 방향을 직접 유도하는 장치입니다.

- **담당:** 프로젝트 총괄, 모터 구동·조향 제어, 회로 설계 및 하드웨어 제작
- ESP32 중앙 제어기에서 BLE(앱) · UART(Raspberry Pi, TFmini) · PWM(MDD10A 모터드라이버)을 통합
- 장애물 > 신호 > 횡단보도 > 길안내 순의 **제어 우선순위** 설계
- 장애물 연속 검출·히스테리시스(30 cm 진입 / 40 cm 해제)와 역토크 경고
- [▶ 시연 영상](https://youtu.be/FR7wWThx7Qo)

### 🏪 [Bootivation — 무인매장 고객·배달기사 검증 시스템](https://github.com/samareosa-cloud/2026_Bootivation)
`2026 SSG-SSAC 해커톤` · ATmega128 · Raspberry Pi 5 · ZeroMQ

Vision · POS · 트레이 · 배달 안내 장치를 하나의 상태머신으로 묶어 결제 누락과 오픽업을 검증하는 시스템입니다.

- **담당:** ATmega128 POS 펌웨어, Raspberry Pi 트레이 인식·음성 안내
- 기존 **어셈블리 코드를 분석해 기능별 C 모듈로 재구성** (AVR-GCC)
- 초음파·IR·터치·조이스틱 입력, LCD·FND 출력, UART 57600 bps CSV 프로토콜 설계
- HSV 기반 2×2 슬롯 트레이 상품 분류, 프레임 다수결로 수량 안정화

### 📷 [AEEDS — 영상처리 실습](https://github.com/samareosa-cloud/AEEDS)
`전기전자심화설계및소프트웨어실습` · C++ · OpenCV

- 이미지 회전·리사이즈, Gradient Magnitude, HOG, 코너 검출 등을 직접 구현

---

## Tech Stack

| 분야 | 사용 경험 |
|---|---|
| MCU · Firmware | ESP32, ATmega128 (C / ASM), Arduino |
| SBC | Raspberry Pi 5 |
| Sensor · Actuator | TFmini LiDAR, 초음파, IR, DC 모터 + MDD10A, 서보 |
| Communication | UART, BLE, Bluetooth SPP, ZeroMQ |
| Vision | OpenCV (C++ / Python), HSV 색상 분석, YOLO 연동 |
| Language | C, C++, Python, Dart |
| Tools | Arduino IDE, AVR-GCC, Visual Studio, Git |
