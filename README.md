# openchirp-docker
Multi-container docker instances for Openchirp Services. dd

## Openchirp Services

# web
1. Apache : Hosts static angular2 website files (talks to REST)
Source Repo : https://github.com/OpenChirp/website

2. Node.js : Hosts REST Server
Source Repo : https://github.com/OpenChirp/openchirp_rest   

# Databases (talks to REST)
3. Influxdb
4. Mongodb
5. Redis

### MQTT Broker (talks to mongo)
6. Mosquito -> missing: setup basic auth

### Services
7.  TSDB Storage Service ( Python code) (talks to MQTT and REST, influxdb)
Source Repo : https://github.com/OpenChirp/mqtt_tsdb_storage_service
8. Lora Serialization Service( Go code)  (talks to MQTT and REST)
Source Repo : https://github.com/OpenChirp/easybits
