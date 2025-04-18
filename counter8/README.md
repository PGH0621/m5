# 🔢 counter8 — 3비트 이진 LED 카운터

`counter8`는 3개의 LED를 GPIO 핀으로 제어하여  
**0부터 7까지의 숫자를 이진법(Binary)** 으로 표시하는 Bash 스크립트 기반 과제입니다.

---

## ▶ 유튜브 영상
https://youtu.be/JDVbRZOGPuU?si=g2gFv3OpunEK9nc_

---
## 🎯 과제 설명

- LED 3개를 각각 **1의 자리, 2의 자리, 4의 자리**로 활용하여 **3비트 이진수**를 표현합니다.
- 숫자 0부터 7까지 1초 간격으로 순차 출력되며,  
  각 숫자는 LED의 ON/OFF 상태로 시각화됩니다.
- 반복문을 통해 이진수 변환과 LED 제어가 자동으로 이루어집니다.

---

## 💡 핀 구성

|  의미   | GPIO 핀 번호 |
|-------------|---------------|
| 1의 자리     | 23            |
| 2의 자리     | 18            |
| 4의 자리     | 15            |

> LED가 GPIO에 연결되어 있어야 하며, 핀 번호는 `BCM` 기준입니다.

---
## 회로 사진
![image](https://github.com/user-attachments/assets/b69cc987-4186-4910-b86b-8f8a19b09730)

