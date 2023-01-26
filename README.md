# 3AHEL-Theorie-SYS

**table of content**
- [3AHEL-Theorie-SYS](#3ahel-theorie-sys)
  - [MQTT](#mqtt)
    - [In der Schule:](#in-der-schule)
    - [Topics:](#topics)
      - [Für Daheim:](#für-daheim)
  - [Node RED:](#node-red)
    - [Install at Home:](#install-at-home)
      - [Windows:](#windows)
    - [School:](#school)
    - [Server config:](#server-config)
    - [Server save:](#server-save)
  - [Linux:](#linux)
    - [Was ist Linux:](#was-ist-linux)
    - [Starten von Linux:](#starten-von-linux)
___
## MQTT
![imgMQTT](img/csm_mqtt.png)

https://blog.doubleslash.de/mqtt-fuer-dummies/

### In der Schule:
MQTT Broker: iotmqtt.htl-klu.at<br>
Username: htl-IoT<br>
Password: iot..2015<br>
Port: 1883<br>

<br>

### Topics: 
Hierachie - bei uns in der Schule <br>
htl/3xhel/Name/# - gibt alle daten von allen Topics von dieser klasse an.<br>

#### Für Daheim: 
http://mqtt-explorer.com/ ->portable exe
<br>

Topic htl/3ahel/#

<br>
Der mqttexplorer<br>
U:\Programme\iot\tools
<br>
<br>

___
## Node RED: 
### Install at Home:
  https://nodered.org/docs/getting-started/
  #### Windows:
  https://nodered.org/docs/getting-started/windows

### School:
Schule: AlleProgramme\Mikrocontroller\Node-RED<br>
1. Coppy server IP address paste it to your browser

### Server config:
![imgNodeRedConfig](img/node-red-config-server.PNG)

### Server save:
1. alles koppieren
2. rechts oben: Export -> clipboard
3. STRG + C

___
## Linux:
### Was ist Linux:
### Starten von Linux:
cmd: `docker run -it ubuntu`  <br>
Aktuelles verzeichnis aufrufen: `ls` <br>
Verzeichnis wechseln: `cd` change Directory<br>
Verzeichnis erstellen: `mkdir` make Directory <br>
Wichtig!! Linux ist case sensitiv(Groß, Kleinschreibung sind wichtig) <br>
