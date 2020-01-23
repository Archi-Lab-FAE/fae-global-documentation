---
layout: post
title: Swagger-UI Redirect Fix
author: Sven Thomas
categories: guide
---

## Guide
Wird versucht auf das Swagger-UI über den Base-Path des Microservices zuzugreifen, welcher auf /swagger-ui.html weiterleitet, funktioniert dies in der Prod-Umgebung nicht.
Da der MS hinter dem Gateway liegt, wird der Redirect falsch aufgelöst und es wird auf eine komische Adresse (bspw. http://38ca4f775bf7:8080/team-2/) weitergeleitet.

Um das Problem zu beheben muss in der application.yml diese Einstellunge gesetzt werden, damit Spring den Redirect korrekt auflösen kann:

`server.tomcat.use-relative-redirects=true`
