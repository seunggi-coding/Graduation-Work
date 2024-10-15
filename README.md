# Graduation-Work
# 무인서점 시스템

## 프로젝트 개요

이 프로젝트 **무인서점 시스템**은 순천향대학교의 산학 캡스톤 디자인 과제의 일환으로 개발되었습니다. 본 시스템은 IoT 기술을 무인 서점에 통합하여, 사용자가 스마트폰만으로 서점 이용 전 과정을 관리할 수 있도록 설계되었습니다.

주요 목표는 고객이 다음과 같은 기능을 스마트폰으로 간편하게 수행할 수 있도록 하는 것입니다:
- QR 코드를 사용하여 서점 입장
- NFC 기술을 활용한 도서 검색 및 선택
- 사람과의 상호작용 없이 도서 구매
- 재고 및 사용자 데이터의 실시간 업데이트와 함께 서점 퇴장

## 주요 기능

- **NFC 통합**: 각 도서에는 NFC 태그가 부착되어 있어, 사용자가 모바일 기기로 도서 정보를 쉽게 확인할 수 있습니다.
- **QR 코드 입장**: 사용자는 휴대폰으로 고유한 QR 코드를 생성하여 서점에 안전하게 입장할 수 있습니다.
- **자동 결제 시스템**: 결제는 통합된 결제 시스템을 통해 자동으로 처리되어 빠르고 매끄러운 구매 과정을 제공합니다.
- **실시간 재고 관리**: 구매가 완료되면 재고는 자동으로 업데이트되어 수동 관리의 필요성이 줄어듭니다.
- **강화된 보안**: IoT 기술을 활용하여 무인 매장에서 발생할 수 있는 도난 문제를 최소화합니다.

## ⚙ 사용된 기술

- **백엔드**: 사용자 인증, 재고 및 거래 관리를 위한 Spring Boot 기반 서버 구축.
- **프론트엔드**: 사용자 친화적인 인터페이스를 제공하는 React.js로 개발.
- **데이터베이스**: MySQL을 사용하여 사용자 계정, 도서 정보, 거래 기록을 관리.
- **하드웨어 통합**: NFC 리더기 및 QR 코드 스캐너가 시스템 내에서 통합 작동.

## 프로젝트 구조

```plaintext
├── gradle/wrapper
├── src
│   ├── main
│   │   ├── java
│   │   └── resources
├── .gitignore
├── README.md
├── build.gradle
├── gradlew
├── gradlew.bat
└── settings.gradle
```

## 🛠️ 프로젝트 아키텍쳐

![그림1](https://github.com/user-attachments/assets/e7e005fa-5caf-4f9f-8637-d97405f01178)

## 사용법

- **서점 입장**: 웹 애플리케이션을 열고 로그인하여 QR 코드를 생성하고 서점에 입장합니다.
- **도서 스캔**: 모바일 기기의 NFC 기능을 사용하여 도서를 스캔하고 세부 정보를 확인합니다.
- **구매**: 선택한 도서를 장바구니에 추가하고 결제 과정을 완료합니다.
- **서점 퇴장**: 결제가 완료되면 QR 코드를 다시 스캔하여 서점을 퇴장합니다.

## 🤔 향후 개선 사항

- 사용자의 선호도를 기반으로 도서를 추천하는 **추천 엔진 통합**
- **암호화폐 결제 옵션** 추가
- **AI 기반의 보안 감시 시스템** 도입

## 💁‍♂️ 프로젝트 팀원

|Backend|Frontend|
|:---:|:---:|
| ![](https://github.com/yewon-Noh.png?size=120) | ![](https://github.com/SeongHo-C.png?size=120) |
|[노예원](https://github.com/yewon-Noh)|[이성호](https://github.com/SeongHo-C)|

- **김혜원** - 백엔드 개발자, 팀장
- **문승기** - 백엔드 개발자
- **백아현** - 프론트엔드 개발자
- **이선주** - 하드웨어 개발자

