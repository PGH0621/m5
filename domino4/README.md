
# 💡 domino4 — 순차 LED 점등 미션

`domino4`는 4개의 LED를 GPIO 핀을 통해 **순차적으로 점등**하는 Bash 스크립트 기반의 프로젝트입니다.  
마치 도미노처럼 LED가 하나씩 차례대로 켜졌다 꺼지며, 이 동작은 반복됩니다.

---
## ▶ 유튜브 영상
https://youtu.be/0_4YkKwnF3g?si=yrpoGscIAYSVUvvE


---

## 🎯 미션 설명

- 사용자는 `pinctrl` 명령어를 통해 **LED를 제어**합니다.
- 4개의 LED는 1초 간격으로 **차례대로 켜졌다 꺼지는 패턴**을 반복합니다.
- 반복적인 동작을 통해 **하드웨어 제어의 기본 흐름**을 익히는 것이 목표입니다.

---

## 🛠 사용 핀

| LED | GPIO 핀 번호 |
|-----|--------------|
|  1  |     14       |
|  2  |     15       |
|  3  |     18       |
|  4  |     23       |

모든 핀은 출력(`op`) 모드로 설정되며, 시작 시 초기 상태는 OFF(`dl`)입니다.

---
## 회로 사진
![image](https://github.com/user-attachments/assets/d48eb8a1-e78b-46c8-95ea-95ba745dbfc9)
![image](https://github.com/user-attachments/assets/f8aef075-f012-4dd5-af4b-6a07daeb3e2f)
![image](https://github.com/user-attachments/assets/b91167f5-109a-4eeb-9434-0a8f28fe1f06)

