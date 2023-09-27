### Test eclipse-mosquitto
sudo apt-get install mosquitto-clients  
mosquitto_sub -h localhost -t Try/MQTT/Docker  
mosquitto_pub -h localhost -t Try/MQTT/Docker -m "Test Message"  
mosquitto_pub -h localhost -t Try/MQTT/Docker -m "Test Message" -u user -P user


