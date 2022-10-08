

## Internet Of Things


### PROJETO

O projeto consiste em obter dados de sensores e apresentar graficamente as informações de Temperatura, Umidade e Conectores da residência.

![Simulaçãoa](https://user-images.githubusercontent.com/63813811/194684410-e9b8af83-f2b4-47ad-8d09-da22dfc13b7f.png)

## Aplicabilidade



projeto que auxiliará na vida das pessoas o deixando mais informada a respeito da situação meteorológica ao redor da sua residência com auxílio de sensores, e assim facilitando a vida do usuário.

### RequesT

 https://api.thingspeak.com/channels/1053267/feeds.json?results=2
  
+ Response 200 (application/json)

    + Body

            {
                 {
  "channel": {
    "id": 1053267,
    "name": "Final Project",
    "description": "Canal para armazenar dados de Lab08\r\n",
    "latitude": "0.0",
    "longitude": "0.0",
    "field1": "TEMPERATURA",
    "field2": "LAMPADA",
    "field3": "UMIDADE",
    "created_at": "2020-05-05T14:28:23Z",
    "updated_at": "2020-05-29T15:43:24Z",
    "last_entry_id": 246
  },
  "feeds": [
    {
      "created_at": "2022-10-08T02:55:20Z",
      "entry_id": 245,
      "field1": "30",
      "field2": "1",
      "field3": "43"
    },
    {
      "created_at": "2022-10-08T02:56:40Z",
      "entry_id": 246,
      "field1": "0",
      "field2": null,
      "field3": null
    }
  ]
}
            }


### Tks!
