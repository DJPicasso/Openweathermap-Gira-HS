# Weather Information based on Openweathermap API
 Openweathermap for Gira Homeserver

Information regarding API 3.0 you will find here: https://openweathermap.org/api/one-call-3

To get the information you need to make an API call
https://api.openweathermap.org/data/3.0/onecall?lat={lat}&lon={lon}&exclude={part}&appid={API key}&units={units}&lang={language}

The API call you can specify via Web-Request/IP-Request in the homeserver
![grafik](https://github.com/user-attachments/assets/caf1665f-58a9-4fc6-a683-bfd16af53f8b)

![grafik](https://github.com/user-attachments/assets/2b8077e4-1563-42ee-9478-25a7d4eef3ba)

![grafik](https://github.com/user-attachments/assets/5f2525f0-9476-499f-99f5-91b78ccae17a)


This LM (logic module) supports:
- current
- hourly
- daily

Therefore you need to configure input (E3 current=1/hour=2/day=3).



Logic in Gira Homeserver
![grafik](https://github.com/user-attachments/assets/22630b76-7bd7-428d-977c-014464f98792)


Example for current weather
![grafik](https://github.com/user-attachments/assets/c436e182-e57f-4e30-99af-55c4afce4826)

Current weather information in VISU

![grafik](https://github.com/user-attachments/assets/76e5da28-3cbd-47a2-a2ea-d2c937b05489)


Example for daily weather (0, 1, 2, 3)
![grafik](https://github.com/user-attachments/assets/da71461e-912c-4cd9-94ca-a7b6bdd5654e)

Daily weather information in VISU

0 = today, 1 = tomorrow, 2 = in 2 days, 3 = in 3 days
![grafik](https://github.com/user-attachments/assets/bc7bf27e-af0c-49d7-835c-297cf326fe65)
