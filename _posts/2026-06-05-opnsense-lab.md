---
layout: post
title: "OPNsense를 활용한 가상 보안 실험실(Lab) 환경 구축 가이드"
date: 2026-06-05 12:00:00 +0900
category: Security
image: assets/images/blog/blog6.jpg
author: LeeKyoungCheol
tags: opnsense infrastructure
---

### 가이드 개요
VMware 인프라 환경 위에서 오픈소스 방화벽인 OPNsense를 설정하고, 안전한 모의 침투 실습을 진행할 수 있는 독자적인 보안 네트워크 랩을 설계하는 과정을 단계별로 정리했습니다.

### 환경 구축 핵심 요소
* **방화벽 인터페이스 설정:** WAN(외부망), DMZ(서버망), LAN(내부 신뢰망) 구간 완벽 분리
* **접근 제어 규칙(ACL):** 정책 기반의 인바운드/아웃바운드 트래픽 통제 규칙 적용
* **테스트베드 검증:** 구간 간 비인가 접근 차단 여부 테스트 및 보안성 평가 진행