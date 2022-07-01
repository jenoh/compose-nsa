# Monitoring
Notre stack de monitoring est composée de :

## Influxdata
Après [installation](https://docs.influxdata.com/influxdb/v2.0/install/), localhost:8086 permet d'atteindre l'interface influxdb qui nous guide pour la configuration initiale. 
Les différents dashboards que nous avons créés ainsi que les variables nécessaires à leur fonctionnement sont disponibles au format JSON [ici](../influxdata/).

### PagerDuty
PagerDuty est configuré comme point de notification pour nos alertes et permet (notamment) l'envoi de mails.

## Telegraf
[Telegraf](https://docs.influxdata.com/telegraf/v1.23/) est l'agent de collection qui envoie les données à influx grâce à ses nombreux [plugins](https://docs.influxdata.com/telegraf/v1.23/plugins/).