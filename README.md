# Arduino-Airplane
Arduino airplane with MPU-6050(GY-521) 6DOF sensor and SG90 servo motor and visualize using processing

## 아두이노 비행기
- MPU-6050(GY-521) 6축 자이로 센서 1개
- SG90 서보모터 1개

## processing을 이용한 시각화
1. processing 설치
2. processing 라이브러리 폴더에 toxiclibs_p5, toxiclibscore 추가
3. arduino_airplane_processing.pde 파일 실행

## processing 포트 설정
0. 아두이노에 비행기 코드 업로드 후 processing 실행
1. 39번 줄 port = new Serial(this, "COM3", 115200); 주석 해제 후 자신의 포트 이름으로 변경
2. 만약 맥북 사용중이어도 아두이노에서 잡히는 포트 이름 그대로 변경 (/dev/cu.usbserial-120)
