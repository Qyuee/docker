"Clickhouse 서버 실행"  
- docker run -d --name some-clickhouse-server --ulimit nofile=262144:262144 yandex/clickhouse-server