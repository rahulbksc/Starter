# Temperature Sensor Simulation

This example demonstrate a sensor data emitting real-time temperature.
User can provide a config to chose a scale (Fahrenheit, Celsius, Kelvin)

please follow instruction @ https://docs.docker.com/get-docker/


To build docker container use follownig commands:

```
cd sensor

sudo docker build . -t sensor `

```

#To run the container:

```sudo docker run -p 80:80 sensor:latest```

Open a browser and type http://127.0.0.1:80

## For windows versions before windows 10

### Run without docker
1. Install Python (3.8.5) from https://www.python.org/downloads/
2. Install Flask using steps listed [here](https://flask.palletsprojects.com/en/1.1.x/installation/). See section for Windows.

### Install Virtualbox and create a ubuntu virtual machine using
https://www.krizna.com/windows-7/install-ubuntu-windows-7-virtualbox/
