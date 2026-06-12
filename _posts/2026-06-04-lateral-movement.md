---
layout: post
title: "내부망 보안의 핵심: Lateral Movement 탐지 및 차단 기법"
date: 2026-06-04 12:00:00 +0900
category: Security
image: assets/images/blog/blog5.jpg
author: LeeKyoungCheol
tags: network security
---

### 포스팅 개요
공격자가 내부 네트워크에 침투한 이후, 다른 시스템으로 권한을 상승시키며 이동하는 측면 이동(Lateral Movement) 기법의 위험성을 진단하고 이를 억제하기 위한 방안을 공유합니다.

### 주요 대응 전략
* **네트워크 세분화:** 인프라 구간을 세부 서브넷으로 격리하여 이동 경로 차단
* **이상 트래픽 탐지:** 내부 호스트 간의 비정상적인 연결 요청 및 권한 탈취 시도 실시간 모니터링
* **인증 관리 강화:** 내부망 세션 관리 및 비인가 접근 제어 정책 고도화