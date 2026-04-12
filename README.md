# Z-Flip-RoboCase: AI-Powered Robotic Case for Galaxy Z Flip

### 🇰🇷 프로젝트 소개
이 프로젝트는 갤럭시 Z 플립의 독특한 폼팩터(약 80도 이상의 폴딩)를 활용한 **오픈소스 로봇 케이스**입니다. 3D 프린터 없이 기존 스마트폰 케이스에 마이크로비트와 360도 서보모터를 결합하여 스마트폰을 로봇으로 변신시킵니다. 별도의 앱 설치 없이 웹 브라우저(Web Bluetooth)만으로 인공지능 제어가 가능합니다.

### 🇺🇸 Project Introduction
An **Open-Source Robotic Case** designed for the Galaxy Z Flip. You don't need a 3D printer; it utilizes an existing smartphone case combined with a Micro:bit and 360-degree servo motors. It features AI-driven control via Web Bluetooth without any app installation.

---

## 🔗 Control Website (제어 사이트)

**[Interactive AI Face & Control Center]**
👉 [https://magenta-scone-05a35c.netlify.app](https://magenta-scone-05a35c.netlify.app)

* **Mouse/Touch Interaction:** * 🇰🇷 눈동자가 커서나 손가락을 따라다니며, 클릭 시 랜덤하게 8가지 표정(평상시, 행복함, 화남, 슬픔, 호기심, 놀람, 졸림, 사랑)으로 변합니다.
  * 🇺🇸 Eyes follow the cursor/finger. Clicking triggers 8 random expressions (Normal, Happy, Angry, Sad, Curious, Surprised, Sleepy, Love).
* **AI Finger Tracking:** * 🇰🇷 '손가락 추적 켜기'를 통해 카메라가 켜지면 검지손가락을 따라다니고, 검지와 엄지를 붙였다 떼면 표정이 바뀝니다. (노트북/스마트폰 모두 지원)
  * 🇺🇸 Enable 'Finger Tracking' to follow your index finger using the camera. Pinching (bringing thumb and index finger together) changes the expression. (Supports both laptops and smartphones)

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
