# Weather Information based on Openweathermap API
 Openweathermap for Gira Homeserver

Information regarding API 3.0 you will find here: https://openweathermap.org/api/one-call-3


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
![grafik](https://github.com/user-attachments/assets/d0e82cb5-ed3a-4362-9b40-4848b6daf96e)


Daily weather information in VISU

0 = today, 1 = tomorrow, 2 = in 2 days, 3 = in 3 days
![grafik](https://github.com/user-attachments/assets/bc7bf27e-af0c-49d7-835c-297cf326fe65)

Configuring the Gira Homeserver to get the OpenWeathermap data

To get the information you need to make an API call
https://api.openweathermap.org/data/3.0/onecall?lat={lat}&lon={lon}&exclude={part}&appid={API_key}&units={units}&lang={language}

The API call you can specify via Web-Request/IP-Request in the homeserver
![grafik](https://github.com/user-attachments/assets/8030cb03-494b-481e-bd52-73c373b6f34a)

![grafik](https://github.com/user-attachments/assets/7b1e89e7-8fb3-44cb-a8c8-6e93f52d3ba0)

![grafik](https://github.com/user-attachments/assets/05841b4f-df53-484d-91a7-0b6402a3bd21)


Dynamic Icons
For getting individualized icons you should use the functionality "dynamic symbols" in Gira Homeserver.
There are several sites where you can download weather icons.
My settings are
![grafik](https://github.com/user-attachments/assets/4d5398ac-f5e2-4694-abde-ec43d95f2a12)

Rain Risk

![grafik](https://github.com/user-attachments/assets/cf58c3c1-5708-439b-832e-7de9bc2a34fa)

Wind direction

![grafik](https://github.com/user-attachments/assets/0ef22559-c538-4381-8d5f-f8b2a4877bf6)

