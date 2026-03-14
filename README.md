# Smart Building Home Lab

A home automation and monitoring environment built to experiment with smart building technologies.

This project demonstrates how self-hosted tools can be used to monitor environmental conditions, automate devices, and visualize system data.

## Technologies Used

- Home Assistant
- Grafana
- InfluxDB
- Linux Server
- MQTT

## Architecture

Devices and sensors send data to Home Assistant which stores telemetry in InfluxDB. Grafana dashboards visualize the data and automation rules trigger alerts or actions.

Example pipeline:

Sensors → Home Assistant → InfluxDB → Grafana Dashboard → Automations

## Features

- Device monitoring
- Environmental tracking
- Automation rules
- Dashboard visualization
- Home server deployment

## Screenshots

(Add dashboard screenshots here)

## Future Improvements

- HVAC performance monitoring
- Predictive maintenance alerts
- Energy usage tracking
