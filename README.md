# MONITORING-STACK

NAS에서 실행되고 있는 모든 컨테이너들과 하드웨어를 통합 모니터링하기 위한 프로젝트입니다.

<br/>
<br/>

### DashBoard
- **Grafana**

<br/>

### DataBase
- **Prometheus**
- **Loki**

<br/>

### Agents
- `node_exporter`: 하드웨어 및 OS 수준의 메트릭을 수집.
- `mariadb_exporter`: MariaDB의 내부 DB 상태 및 성능 지표를 수집.
- `cadvisor`: Docker 컨테이너별 리소스 사용률 정보를 수집.
- `promtail`: Docker 컨테이너 내부 로그 정보를 수집.

<br/>

### Architecture
---

![Monitoring](https://jh8459.s3.ap-northeast-2.amazonaws.com/monitoring/architecture.png)

### Example
---

![Example](https://jh8459.s3.ap-northeast-2.amazonaws.com/monitoring/sample.png)
