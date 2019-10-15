---
layout: post
title: Apache Kafka als Standard für Message Queues
author: Stefan Bente
categories: global
---

### Definition:
Als Message Queue (für das Versenden / Konsumieren von Events) ist Apache Kafka gesetzt.

Grund dafür ist, dass die verwendete Message Queue in allen Services einheitlich sein muss (sonst gibt es ja keine Kommunikation ...). Des weiteren ist erfahrungsgemäß  das Aufsetzen einer Message Queue sehr arbeitsaufwändig und fehlerträchtig. Dies soll nicht Ihr Fokus in FAE sein. Damit das wir Ihnen sinnvoll helfen können, müssen Sie eine Queue verwenden, die wir gut kennen. Wir setzen Kafka in Eigenentwicklungen ein und haben viel Erfahrung damit. Apache Kafka wird vorkonfiguriert zur Verfügung gestellt.