## Logtrail Configuration Examples
This repo contains list of example recommended configurations for [Logtrail](https://github.com/sivasamyk/logtrail) Kibana plugin.

Each directory contains following files:

* **sample log file** : Example log file
* **logstash.conf** : Logstash configuration file for parsing the log file. Assumes the timestamps of incoming messages are in UTC if not explicitly present in timestamp.
* **logtrail.json** : Logtrail plugin configuration
* **screenshot** : Example logtrail screenshot

*Note: Change the input and output plugins in logstash configuration as per your needs.*
