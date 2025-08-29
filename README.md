----
----

#  NginxReverse addon  #

Accedi alla pagina della centralina da Home Assistant

  * [NginxReverse-Homeassistant](https://github.com/sdavides/NginxReverse-Homeassistant)

      * ( required "apache" - "fix_resource_proxy_redirect" enable )

![immagine](https://github.com/user-attachments/assets/6f408af1-c3b2-4ad3-aece-fc118387fef0)

  
----

----


#  Siqura Allarme CasaSicura.it on HomeAssistant #

Goal: Siqura Alarm like Meian/Emooluxr (CasaSicura.it/Antifurto365.it) on HomeAssistant

  * note: 
	* this flow is example and was developed for "Siqura" (CasaSicura.it)

![immagine](https://github.com/sdavides/sdavides-meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/4bd246c2-d8a4-4c44-9af6-84b9ed796af7)


## Requirement for NodeRed (recommended) ##
* NodeRed HomeAssistant
  * node-red-contrib-ialarm (palette)
  * node-red-contrib-home-assistant-websocket (palette)
  * node-red-contrib-ha-mqtt (palette)

* NodeRed Companion on HomeAssistant
* Mosquitto broker on HomeAssistant
	
## Method ##
* Method 1 NodeRed (recommended):
	* Import flow json 
	* Replace your value "ialarm-server" node
 	* Copy and paste config_mqtt_ha.txt on configuration.yaml
	* Deploy
	
* Method 2 RestFul (without NodeRed):
	* Replace your value into rest_post_command_without_Nodered.txt
	* Copy and paste rest_post_command_without_Nodered.txt on configuration.yaml
	* Restart HomeAssistant

 
## Configuration NodeRed ##

![283607086-423bf18e-417a-46bd-9542-e77cf82b51e4](https://github.com/sdavides/meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/a630cc1e-a079-4326-a758-5b7e904e4dee)

   * Add config on file "/homeassistant/configuration.yaml" (config_mqtt_ha.txt)
   * Edit Mosquitto node with your configuration

![283607165-9136f59f-7764-4ed9-95ec-9aab2677dd43](https://github.com/sdavides/meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/da3b0a44-ac7f-47a3-9f11-8b399750701e)

---

## Result ##

![283607268-f7406c82-380a-4595-9d9b-8b4eacdd5020](https://github.com/sdavides/meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/dcc5dc3b-b365-46ec-8371-baef2f491de1)

![283607338-2f4d4eef-ff4a-40a0-aa12-b7f23a52402b](https://github.com/sdavides/meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/b5d230c2-5d23-45f3-b7be-40b429df6fae)

![283607431-7af50db1-1f0e-4914-a74a-75693dabd16d](https://github.com/sdavides/meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/a915386e-7fe8-44c0-90e4-a11a4ba6bdd0)

---

## TIPS ##

* Set config by command string

![283607685-d35dd086-1f13-40a7-9793-2fc4d70a2cb8](https://github.com/sdavides/meian-Siqura_CasaSicuraAlarm-Homeassistant/assets/31100253/c97485a8-c5b3-40ab-847f-f78a394de16f)

---

## See also ##

[ialarm-mqtt](https://github.com/maxill1/ialarm-mqtt)
     
[meian-client](https://github.com/wildstray/meian-client)
