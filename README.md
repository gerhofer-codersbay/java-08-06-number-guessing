# Zahlen raten via HTTP

Implementiere einen einfachen [HTTP Server](https://docs.oracle.com/en/java/javase/14/docs/api/jdk.httpserver/com/sun/net/httpserver/HttpServer.html), der sich zu Beginn eine Zahl ausdenkt. 
Über einen Request soll ein Tipp abgegeben werden können, z.B. über localhost:1337/guessing?guess=12

Ist 12 zu hoch, sollte der Server mit "Lower" Antworten, ist 12 zu niedrig, sollte der Server mit "Higher" antworten und sobald die Zahl erraten wurde, sollte mit "Richtig!" geantwortet werden und der Server sollte sich eine neue Zahl ausdenken
