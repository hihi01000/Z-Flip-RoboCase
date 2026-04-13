# Z-Flip-RoboCase: AI-Powered Robotic Case for Galaxy Z Flip

### 🇰🇷 프로젝트 소개

![Z-Flip-RoboCase 한글 소개 만화](images/comic_ko.png)

이 프로젝트는 갤럭시 Z 플립의 독특한 폼팩터(약 80도 이상의 폴딩)를 활용한 **오픈소스 로봇 케이스**입니다. 3D 프린터 없이 기존 스마트폰 케이스에 마이크로비트와 360도 서보모터를 결합하여 스마트폰을 로봇으로 변신시킵니다. 별도의 앱 설치 없이 웹 브라우저(Web Bluetooth)만으로 인공지능 제어가 가능합니다.

### 🇺🇸 Project Introduction

![Z-Flip-RoboCase English Introduction Comic](images/comic_en.png)

An **Open-Source Robotic Case** designed for the Galaxy Z Flip. It transforms a smartphone into a robot using Micro:bit and 360-degree servo motors on an existing case. It features AI-driven control via Web Bluetooth without any app installation.

---

## 🔗 Control System & Demos (제어 시스템 및 작동 영상)

### 1. 외부 화면 및 AI 인터페이스 데모 (v1 - Cover Screen & AI Face Demo)

👉 **[제어 사이트 (Control Website)](https://magenta-scone-05a35c.netlify.app)**

* **Mouse/Touch Interaction:** * 🇰🇷 눈동자가 커서나 손가락을 따라다니며, 클릭 시 랜덤하게 8가지 표정(평상시, 행복함, 화남, 슬픔, 호기심, 놀람, 졸림, 사랑)으로 변합니다.
  * 🇺🇸 Eyes follow the cursor/finger. Clicking triggers 8 random expressions.
* **AI Finger Tracking:** * 🇰🇷 '손가락 추적 켜기'를 통해 카메라가 켜지면 검지손가락을 따라다니고, 검지와 엄지를 붙였다 떼면 표정이 바뀝니다.
  * 🇺🇸 Enable 'Finger Tracking' to follow your index finger using the camera. Pinching changes the expression.
* 🇰🇷 최종 로봇 조립 전, Z 플립의 외부 화면이 제어 사이트와 성공적으로 연동되는 모습을 담은 초기 데모입니다.

*(👇 아래 이미지를 클릭하면 영상이 재생됩니다 / Click the image below to watch the video)*

[![초기 버전 데모 영상](https://img.youtube.com/vi/8tVqE9OLXx8/0.jpg)](https://www.youtube.com/shorts/8tVqE9OLXx8)

### 2. 웹 블루투스 모터 제어 데모 (v2 - Web Bluetooth Motor Control Test)

👉 **[테스트 사이트 (Test Website - CodePen)](https://codepen.io/nwockltm-the-encoder/full/QwyQLOG)**
👉 **[마이크로비트 소스 코드 (Micro:bit Source Code)](https://makecode.microbit.org/S11292-29001-99587-59826)**

* 🇰🇷 다른 스마트폰으로 웹사이트에 접속하여, Z 플립의 전원을 사용하는 마이크로비트와 웹 블루투스로 무선 연결한 뒤 서보모터를 작동시키는 테스트입니다. 모터 구동을 위해 위 링크의 마이크로비트 코드를 업로드해야 합니다.
* 🇺🇸 This test verifies Web Bluetooth functionality. Using another smartphone, we accessed the web browser and connected to the Micro:bit. You need to upload the Micro:bit code provided above to operate the motors.

*(👇 아래 이미지를 클릭하면 영상이 재생됩니다 / Click the image below to watch the video)*

[![웹 블루투스 제어 데모 영상](https://img.youtube.com/vi/Pqm7mCUuU8g/0.jpg)](https://www.youtube.com/shorts/Pqm7mCUuU8g)

---

## ✨ Key Features (주요 특징)

* **80°+ Folding Interface:** 내부 디스플레이가 켜지지 않는 최적의 각도(약 80도 이상)로 세워, 외부 디스플레이를 로봇의 얼굴로 온전히 활용합니다.
* **Web Bluetooth Control:** 웹 브라우저에서 마이크로비트를 직접 제어합니다.
* **AI Interaction:** 카메라 인식을 통해 손가락, 얼굴, 음성으로 로봇을 움직입니다.
* **Smartphone-Powered:** 갤럭시 Z 플립의 전원을 직접 사용하여 배터리가 필요 없습니다.
* **High Accessibility:** 3D 프린팅 없이 기성품 케이스와 범용 부품만으로 제작이 가능합니다.

---

## 🛠 Hardware (준비물)

* **Smartphone & Case:** Samsung Galaxy Z Flip Series 및 일반 스마트폰 케이스 (Existing smartphone case)
* **Controller:** BBC Micro:bit v2
* **Actuator:** 360-degree Servo Motors (x2): **[ELECFREAKS] EF90D 360-degree Digital Servo for Micro:bit [EF09081]**
* **Mobility:** 볼 캐스터 (Ball Caster)
* **Expansion Board (마이크로비트 확장 보드):** * 🇰🇷 Z 플립에서 직접 전원을 공급받으므로, **별도의 외부 전원이 필요 없는 확장 보드라면 어떤 제품이든 무방합니다.**
  * 🇺🇸 Any Micro:bit expansion board that does not require an external power supply can be used.

---

## 📜 License & Vision (라이선스 및 비전)

**🇰🇷 Korean**
누구나 이 아이디어로 새로운 가치를 만들어도 좋습니다. 상업적 이용도 허용합니다. 다만, 이 프로젝트의 최초 아이디어 제안자가 **용문중학교 정영천(Young-chun Jung)**임을 명시해 주시기 바랍니다. (MIT 라이선스 적용)

**🇺🇸 English**
Anyone is free to create new value with this idea. Commercial use is fully permitted. However, we simply request that you credit the original creator of this project as **Young-chun Jung (Yongmoon Middle School)**. (Licensed under MIT)
