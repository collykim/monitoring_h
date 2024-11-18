# monitoring_h
Server resource monitoring with prometheus and grafana

### 아키텍처 다이어그램

![image](https://github.com/user-attachments/assets/16ae0e80-0c2a-4f73-b7af-6e1da7fbafd3)




### grafana 도입 이유
기존 사용중인 모니터링 툴이 있지만 정확하지 않다.
   -> CPU사용량이 -로 표시되는 등 서버 자원 상황을 정확하게 확인할 수 없음

### 데이터 흐름
nodeexporter를 이용해서 prometheus에 저장 
grafana로 서버 자원 확인


#### 실제 서비스에 도입한다기 보단 운영자의 측면에서 좀 더 확실한 자원 사용량을 확인하고 싶어 도입


