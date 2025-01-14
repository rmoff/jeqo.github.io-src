---
title: Projects
date: 2021-12-04
---

## Open-source

### [Apache Kafka](kafka.apache.org/)

https://github.com/apache/kafka

Main contributions:

- Author of the following improvement proposals (KIP):
  - KIP-122: https://cwiki.apache.org/confluence/display/KAFKA/KIP-122%3A+Add+Reset+Consumer+Group+Offsets+tooling
  - KIP-171: https://cwiki.apache.org/confluence/display/KAFKA/KIP-171+-+Extend+Consumer+Group+Reset+Offset+for+Stream+Application
  - KIP-244: https://cwiki.apache.org/confluence/display/KAFKA/KIP-244%3A+Add+Record+Header+support+to+Kafka+Streams+Processor+API
  - KIP-634: https://cwiki.apache.org/confluence/display/KAFKA/KIP-634%3A+Complementary+support+for+headers+and+record+metadata+in+Kafka+Streams+DSL
  - KIP-666: https://cwiki.apache.org/confluence/display/KAFKA/KIP-666%3A+Add+Instant-based+methods+to+ReadOnlySessionStore
  - KIP-667: https://cwiki.apache.org/confluence/display/KAFKA/KIP-667%3A+Remove+deprecated+methods+from+ReadOnlyWindowStore
- Helped with the implementation of:
  - KIP-478: 
    - https://cwiki.apache.org/confluence/display/KAFKA/KIP-478+-+Strongly+typed+Processor+API
    - https://issues.apache.org/jira/browse/KAFKA-8410

### [Zipkin](https://zipkin.io/)

https://github.com/openzipkin/zipkin

Main contributions:

- Zipkin storage based on Kafka Streams: https://github.com/openzipkin-contrib/zipkin-storage-kafka
- Brave support for Kafka clients and streams: https://github.com/openzipkin/brave
- Maintaining Zipkin usage of Kafka as collector: https://github.com/openzipkin/zipkin-reporter-java
- Kafka interceptors for Zipkin tracing: https://github.com/openzipkin-contrib/brave-kafka-interceptor

### [Open Politica](https://openpolitica.com/)

https://github.com/openpolitica

Helped with:

- Collecting data from public institutions
  - https://github.com/openpolitica/jne-elecciones/
  - https://github.com/openpolitica/congreso-proyecto-ley
- Design the collection of Peruvian Congress votes:
  - https://github.com/openpolitica/congreso-pleno-asistencia-votacion/
  - https://github.com/openpolitica/congreso-pleno 
