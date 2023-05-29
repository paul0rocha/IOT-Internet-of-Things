## Internet Of Things


 ![Img](https://user-images.githubusercontent.com/63813811/194684410-e9b8af83-f2b4-47ad-8d09-da22dfc13b7f.png)



## About this Project

The idea of ​​the program is:

_"The project consists of obtaining data from sensors and graphically presenting information on Temperature, Humidity and Connectors of the residence."_

**PS:** During the development of the project, we used the Tinkercad platform to simulate the home environment and, with that, we used the sensors to capture the data and send it via the RestFull API to the thinkspeack endpoint, thus controlling the calls and data submissions.

🤩:**


## Some notes about this app

1 - Thingspeak: Control of POST / GET requests

2 - Thinkecard: Control of electronic devices




 ### RequesT

 https://api.thingspeak.com/channels/1053267/feeds.json?results=2
  
+ Response 200 (application/json)


    + Body

            {
                   'channel': {
                     'id': 1053267,
                     'name': 'Final Project',
                     'description': 'Canal para armazenar dados de Lab08\r\n',
                     'latitude': '0.0',
                     'longitude': '0.0',
                     'field1': 'TEMPERATURA',
                     'field2': 'LAMPADA',
                     'field3': 'UMIDADE',
                     'created_at': '2020-05-05T14:28:23Z',
                     'updated_at': '2020-05-29T15:43:24Z',
                     'last_entry_id': 247
           },
                     'feeds': [
            {
                      'created_at': '2022-10-08T02:56:40Z',
                      'entry_id': 246,
                      'field1': '0',
                      'field2': null,
                      'field3': null
            },
            {
                      'created_at': '2022-10-08T03:01:25Z',
                      'entry_id': 247,
                      'field1': '30',
                      'field2': '1',
                      'field3': '43'
            }
          ]
          }


**Installing dependencies**


```
pip install pycep-correios==4.0.3
```
 ![Img](https://github.com/steniowagner/mindCast/assets/63813811/46842741-3b16-4ed8-bb08-30cbd75e59d9)




## Contributing

You can send how many PR's do you want, I'll be glad to analyse and accept them! And if you have any question about the project...

Email-me: pauloseng80@gmail.com.com

Connect with me at [LinkedIn](https://www.linkedin.com/in/pauloroch/)

Thank you!

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/paul0rocha/mindCast/blob/master/LICENSE) file for details

