# Flight Simulation Study

Unreal Engine 5.3으로 비행 시뮬레이터를 학습하며 제작한 프로젝트 기록입니다. 저장소에는 최종 완성본이 표시되며, Git 커밋 기록을 통해 초기 실습부터 완성본까지의 발전 과정을 확인할 수 있습니다.

## 프로젝트 순서

1. 2026-09-19 커밋 — 초기 실습본
2. 2026-09-20 커밋 — 발전 버전
3. 2026-09-28 커밋 — 최종 완성본

각 단계는 동일한 `FlightSim` 프로젝트 폴더로 기록되어 있어 커밋 간 변경 사항을 비교할 수 있습니다.

## 학습 내용

- Unreal Engine 5.3 프로젝트 구성과 레벨 제작
- Cesium for Unreal을 이용한 지형 및 지리 공간 기능 활용
- JSBSim 기반 비행역학 연동
- GeoReferencing과 Sun Position 기능 활용
- Raw Input을 통한 입력 장치 연동
- Blueprint와 C++ 모듈을 활용한 비행 시뮬레이션 구현

## 실행

각 버전 폴더의 `.uproject` 파일을 Unreal Engine 5.3에서 엽니다. 최종본은 `FlightSim/FlightSim.uproject`입니다.

프로젝트에서 사용하는 Marketplace 플러그인(예: Cesium for Unreal)이 설치되어 있어야 합니다. 처음 실행할 때 제외된 빌드 산출물과 캐시는 Unreal Engine이 다시 생성합니다.

## 저장소 안내

GitHub 용량을 줄이기 위해 ZIP 백업, `Binaries`, `Intermediate`, `DerivedDataCache`, `Saved`, IDE 캐시 및 로컬 Cesium 요청 캐시는 저장소에서 제외했습니다. 또한 50MB가 넘는 9월 20일 버전의 `SK_CommercialPlane_LOD0.uasset`은 로컬에만 보관합니다. 나머지 프로젝트 소스, 설정, 콘텐츠와 플러그인 소스는 포함합니다.

