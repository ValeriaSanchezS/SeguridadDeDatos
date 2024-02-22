# Apuntes 

SIEM

### Beats 
Firebeat, winlogbeat(ya tiene los patrones de eventos), Metricbeat, Packetbeat: Agentes que se instalan en el objetivo final para mandar los eventos.

**Homologados**: Que deben tener la misma relacion o correlacion los datos para que coincidan, se deben normalizar. 

Tipos de asociaciones para registrar un evento: 
* date
* time
* user
* resourse 
* action 

### Logstash 

### Elasticsearch 
Centraliza lo que genere eventos, los recolecta y los envia. 

¿Cuanto dura los datos que se recolectan(eventos)? 
3 meses a 1 año. Se debe de tener un buen almacenamiento de datos. 


Beats(recolecta)----> Logstash(Organiza)----> Elasticsearch(Almacena)-----> Kibana(Visualiza)

![visual studio code logo](https://www.elastic.co/guide/en/cloud/current/images/ec-logstash-beats-dataflow.png)

