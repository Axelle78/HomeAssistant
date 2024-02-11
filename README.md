Pour l'écran j'ai utilisé :
- Un ESP32 E-paper driver : https://www.amazon.fr/dp/B07M5CNP3B?psc=1&ref=ppx_yo2ov_dt_b_product_details
- Un ecran Waveshare 7.5 inch E-Paper Display: https://www.amazon.fr/dp/B075R4QY3L?psc=1&ref=ppx_yo2ov_dt_b_product_details
- Un cadre de chez action avec une assez grande profondeur : https://www.action.com/fr-fr/p/2566626/cadre-photo-avec-decorations/
- Une batterie externe : sera remplacée par quelque chose de plus adapté dans le futur

Dans Home Assistant : 
- Module complémentaire ESPHOME pour gérer tout le code du ESP32
- Installation simple : il suffit de le connecter au PC en USB et de lancer ESPHome sur Home assistant (en IP locale), ensuite il demande les informations du WIFI et installe l'ESP32.
- Le code complet de mon écran est disponible de le repository HomeAssistant : https://github.com/Axelle78/HomeAssistant/blob/main/ecran%20e-paper
