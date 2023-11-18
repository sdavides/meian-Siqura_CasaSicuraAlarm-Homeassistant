Goal: Siqura Allarme CasaSicura.it on HomeAssistant

-  this flow is example and was developed for Siqura Alarm like Meian/Emooluxr (CasaSicura.it/Antifurto365.it)
  
![immagine](https://github.com/sdavides/sdavides-meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/4bd246c2-d8a4-4c44-9af6-84b9ed796af7)


---

- Requirement:

NodeRed on HomeAssistant 

"node-red-contrib-ialarm" palette

"node-red-contrib-home-assistant-websocket" palette

"node-red-contrib-ha-mqtt" palette

NodeRed Companion on HomeAssistant

Mosquitto broker on HomeAssistant

---

- Import flow (CasaSicura_NodeRed.json)
- Edit config
- Deploy

![immagine](https://github.com/sdavides/sdavides-meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/423bf18e-417a-46bd-9542-e77cf82b51e4)



- Add config on file "/homeassistant/configuration.yaml" (config_mqtt_ha.txt)

- Edit Mosquitto node with your configuration

 ![immagine](https://github.com/sdavides/sdavides-meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/9136f59f-7764-4ed9-95ec-9aab2677dd43)


---

- Result

  ![immagine](https://github.com/sdavides/sdavides-meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/f7406c82-380a-4595-9d9b-8b4eacdd5020)


  ![immagine](https://github.com/sdavides/sdavides-meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/2f4d4eef-ff4a-40a0-aa12-b7f23a52402b)


  ![immagine](https://github.com/sdavides/sdavides-meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/7af50db1-1f0e-4914-a74a-75693dabd16d)


---

- use rest/post commands if you don't want to use NodeRed

  (rest_post_command_without_Nodered.txt)

---

- Trick
  
  Set config by command

  ![immagine](https://github.com/sdavides/sdavides-meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/d35dd086-1f13-40a7-9793-2fc4d70a2cb8)


