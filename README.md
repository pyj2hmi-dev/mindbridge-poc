# MindBridge PoC

AI 기반 심리상담 초기 접수면접 보조 및 리포트 자동화 시스템 PoC입니다.

## Overview

MindBridge는 심리상담을 대체하는 챗봇이 아니라, 초기 접수면접을 구조화하고 상담사용/사용자용 리포트를 생성하는 보조 시스템입니다.

## My Role

- 서비스 기획 및 문제 정의
- 프롬프트 설계
- 기능 범위 조율
- 리스크 및 역할 경계 정리
- 기획서, 기능정의서, 발표자료 작성
- 발표 및 시연 흐름 구성

## Key Features

- 9섹션 기반 접수면접
- 위기 응답 분기
- 구조화 추출
- 상담사용/사용자용 리포트 생성
- 상담 자원 후보 탐색
- 디버그 및 보안/역할 이탈 대응 설계

## Architecture

- Streamlit UI
- LangChain / LCEL
- Interview Chain
- Extractor Chain
- Crisis Chain
- Report Chain
- JSON / CSV 기반 구조화 데이터 검색

## Demo

- Presentation Deck: 링크 추가
- Demo Video: https://youtu.be/aVzmjp5-fMc
- Portfolio: https://pyj2hmi-dev.github.io/

## Limits

- 심리상담 대체 아님
- 임상 판단 및 진단 수행 안 함
- 자원 탐색은 최종 추천이 아니라 후보 안내
- STT/TTS는 후속 확장 과제
