# Network
NetworkX Library를 활용한 DSME 공정 데이터 네트워크 구조화 및 분석 프로젝트입니다.

전달 받은 데이터 시점에 따라 1차 / 2차 데이터로 구분되어 있습니다.

1차 데이터의 경우 연결 정보가 누락된 것이 많으나, NetworkX Library의 기본적인 기능들의 활용 예시를 볼 수 있는 코드들이 많이 있습니다.
1차 데이터 분석 폴더의 각 코드파일은 다음과 같은 내용을 담고 있습니다.
  DSME NetworkX Test - Basic.ipynb : 그래프 생성, 접근, 특성 추가 및 변경 등 기본 기능 테스트
  DSME NetworkX Test - csv print : 연결 관계가 끊어진 subgraph 단위로 연결리스트 csv 출력 테스트
  DSME NetworkX Test - Visualization.ipynb : Graphviz Library를 활용한 시각화 기능 테스트
  DSME NetworkX Test - CPM.ipynb : Critical Path Method 기능 테스트

2차 데이터의 경우 거의 모든 공정의 연결 정보가 완성되었습니다.
2차 데이터 분석 폴더의 각 코드 파일은 다음과 같은 내용을 담고 있습니다.
  DSME_Network_Process_Analysis.ipynb : 각 공정 종류별 특성 분석

(최종 수정: 2020.09.09)
