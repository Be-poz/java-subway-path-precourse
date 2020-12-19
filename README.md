## 기능 구현 사항

- [ ] 앱이 시작되면서 초기 설정을 한다
  - [x] Station을 생성한다
    - [x] 생성된 역을 최단경로/최단시간 계산 클래스에 추가한다
    - [x] 생성된 역을 StationRepository에 추가한다
  - [x] 노선을 생성한다
    - [x] 생성된 노선을 LineRepository에 추가한다
  - [x] 노선에 역을 등록한다
    - [x] 노선 이름으로 노선을 찾을 수 있다
    - [x] 역 이름으로 역을 찾을 수 있다
    - [x] 인근 역에 대한 정보를 Station 도메인에 집어 넣는다
    - [x] 인근 역에 대한 가중치 정보를 최단거리/시간 계산 클래스에 추가한다

<br/>

<br/>

- [x] 메인 화면을 출력한다
  - [x] 메인 화면에 대한 메뉴 정보를 생성한다
- [x] 원하는 기능을 입력 받는다
  - [x] 선택지 내의 값이어야만 한다
- [ ] 선택한 서비스로 이동할 수 있다
  - [x] 선택지로 서비스를 찾을 수 있다
- [x] 경로 기준 화면을 출력한다
- [x] 경로 기준에 대한 값을 입력 받는다
  - [x] 경로 기준에 대한 메뉴 정보를 생성한다
  - [x] 선택지 내의 값이어야만 한다
- [ ] 선택한 기준으로 계산을 할 수 있다
  - [x] 선택지로 해당 메뉴를 찾을 수 있다
- [x] 출발역을 입력받는다
  - [x] 존재하는 역이어야만 한다
- [x] 도착역을 입력받는다
  - [x] 존재하는 역이어야만 한다
  - [x] 출발역과 다른 역이어야만 한다
- [ ] 최단거리/시간을 계산한다
  - [x] 거리와 시간에 따른 서비스에서 계산한다
  - [x] 계산 클래스를 통해 경로를 계산한다 
  - [ ] 각 역 사이의 거리와 소요 시간을 구한다
    - [ ] 역 이름으로 역을 찾을 수 있다
- [ ] 조회결과를 출력한다

