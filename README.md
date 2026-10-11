# EUNTAEK JEONG · Engineering Portfolio

**FPGA · 임베디드 시스템 · 자율주행 · 회로설계**

신호처리·디지털회로·AI·제어를 회로·보드·차량의 설계와 검증에 연결한 프로젝트입니다. 프로젝트 이름을 누르면 전체 구조와 주요 결과를 볼 수 있고, 상세 문서에서 설계·검증 과정, 코드와 시연을 확인할 수 있습니다.

## 종합설계

### [FPGA 기반 드론 탐지·추적](https://github.com/jounget5411-lab/fpga-drone-portfolio)

카메라 입력부터 AI 추론과 팬틸트 제어까지 **Zybo Z7-20 한 보드에 통합**했습니다. SNN으로 움직임을 감시하고, 비행 후보가 잡히면 CNN으로 위치를 검출하는 두 단계 구조입니다.

`Verilog` · `C/C++` · `AXI/VDMA` · `SNN` · `INT8 CNN`

## 임베디드 시스템

| 프로젝트 | 핵심 설계 |
|---|---|
| [음성인식 기반 조명 제어](https://github.com/jounget5411-lab/embedded-voice-lighting-portfolio) | 두 MCU에 정수 DSP와 추론을 나누고, SPI/UART 통신과 근접 감지를 조명 제어에 연결 |
| [음원 방향 추정·수어 번역](https://github.com/jounget5411-lab/embedded-sensor-fusion-portfolio) | ADC/DMA 음원 입력과 센서 장갑의 특징을 처리하고, 세 STM32 보드를 LED·LCD 출력으로 통합 |
| [접근 감지·사진 선별 저장](https://github.com/jounget5411-lab/embedded-intrusion-detection-portfolio) | STM32 촬영·SPI/DMA 전송과 Zynq의 FreeRTOS 수신·C 추론·SD 저장 연결 |

## 자율주행

| 프로젝트 | 핵심 설계 |
|---|---|
| [국민대학교 자율주행 경진대회](https://github.com/jounget5411-lab/kookmin-autonomous-driving-portfolio) | 카메라·LiDAR 인식을 경로와 제어로 연결하고, 시뮬레이션에서 실차까지 검증 |
| [HL FMA 2025 자율주행](https://github.com/jounget5411-lab/hlfma-2025-portfolio) | GPS·IMU 좌표 기준과 경로 추종을 정리하고, ROS 2와 Arduino 차량 제어 통합 |

## 회로설계

| 프로젝트 | 핵심 설계 |
|---|---|
| [VLSI 풀커스텀](https://github.com/jounget5411-lab/vlsi-full-custom-portfolio) | 클록 생성기와 곱셈 회로의 Schematic·Layout·DRC/LVS·Post-layout 검증 |
| [디지털 RTL](https://github.com/jounget5411-lab/digital-rtl-portfolio) | RISC_TOY CPU의 파이프라인·hazard 처리와 MAC array 행렬곱 가속기 |
| [AER 이벤트 라우터](https://github.com/jounget5411-lab/aer-hardware-portfolio) | 다중 이벤트 입력의 중재·집계·패킷 전달과 계층 구조 검증 · 진행 중 |
