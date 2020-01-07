---
layout: post
title: CommonsRequestLoggingFilter
author: Nils Brenneis
categories: guide
---

## Guide
Für Debugging-Zwecke ist es vorteilhaft Anfragen auf die REST API zu loggen, was mit dem CommonsRequestLoggingFilter einfach möglich ist.
Anstatt im Controller Logging-Ausgaben zu definieren, wird das Logging zentral konfiguriert.
Benötigt werden eine [Config-Klasse](https://github.com/Archi-Lab-FAE/fae-team-4-service/blob/master/src/main/java/de/th/koeln/archilab/fae/faeteam4service/config/RequestLoggingFilterConfig.java) und ein Eintrag in der [project.yml](https://github.com/Archi-Lab-FAE/fae-team-4-service/blob/master/src/main/resources/application.yml), der das Logging-Level definiert.
