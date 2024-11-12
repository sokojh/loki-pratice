# loki 로그 구조 연습
- docker-compose
- Promtail
- Loki
- Grafana
- nginx

# 현재 테스트 구조
Nginx 로그 발생 → Promtail이 감지/수집 → Loki로 전송 → Loki에 저장 → Grafana에서 쿼리/조회
