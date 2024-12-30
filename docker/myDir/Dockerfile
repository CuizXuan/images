version: '2'

networks:
  monitor:
    driver: bridge

services:
  prometheus:
    image: prom/prometheus
    container_name: prometheus
    hostname: prometheus
    restart: always
    volumes:
      - ./prometheus.yml:/etc/prometheus/prometheus.yml
      # - ./node_down.yml:/usr/local/etc/node_down.yml:rw
    ports:
      - "9090:9090"
    networks:
      - monitor


 

