Розгорніть моніторинговий стек для вашого проєкту.

Компоненти:

OpenTelemetry
Prometheus
Fluentbit
Grafana Loki
Grafana

Оцінювання:

Стек розгорнуто та налаштовано у dev-середовищі в Kubernetes для власного проєкту за допомогою Flux. Otel розгорнуто оператором. Fluentbit збирає та експортує логи проєкту та усіх нод кластеру. Проєкт інструментовано для експорту метрик.

20 балів (principal): Проект інструментовано з наскрізним TraceID

____

- Розгорнуто K8S
- Розгорнуто Flux
    - OpenTelemetry
    - Prometheus
    - Fluentbit
    - Grafana Loki
    - Grafana

NAME                                      READY   STATUS    RESTARTS   AGE
fluent-bit-2tmqf                          1/1     Running   0          179m
fluent-bit-bznkj                          1/1     Running   0          3h
fluent-bit-m69sm                          1/1     Running   0          3h
grafana-6db548fd85-rp2cw                  1/1     Running   0          44m
kbot-6d6548d84c-pxwjj                     1/1     Running   0          17h
loki-8758d8c7c-g2bfv                      1/1     Running   0          17h
otel-collector-5f98d654c5-vp2bz           1/1     Running   0          17h
otel-collector-sidecar-57d477fb55-nvd5n   1/1     Running   0          3h13m
prometheus-754854b68-shkvc                1/1     Running   0          17h

Далі не встиг