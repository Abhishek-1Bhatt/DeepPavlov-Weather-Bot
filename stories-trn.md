
## story1
* greet{}
    - utter_greet
    
## story 2
* goodbye{}
    - utter_goodbye
    
## story 3
* ask_weather{"intent": "ask_weather"}
    - utter_ask_location

## story 4
* ask_weather_location{"location": "Moscow"}
    - utter_pleasant

## story 5
* greet{}
    - utter_greet
* ask_weather_location{"location": "stuttgart"}
    - utter_pleasant
* goodbye{}
    - utter_goodbye

## story 6
* greet{}
    - utter_greet
* ask_weather{"intent": "ask_weather"}
    - utter_ask_location
* ask_weather_location{"location": "Berlin"}
    - utter_pleasant
* goodbye{}
    - utter_goodbye

## story 7
* greet{}
    - utter_greet
* ask_weather{"intent": "ask_weather"}
    - utter_ask_location
* ask_weather_location{"location": "Cologne"}
    - utter_pleasant
* goodbye{}
    - utter_goodbye

## story 8
* greet{}
    - utter_greet
* ask_weather{"intent": "ask_weather"}
    - utter_ask_location
* ask_weather_location{"location": "Kiel"}
    - utter_pleasant
* goodbye{}
    - utter_goodbye

## story 9
* greet{}
    - utter_greet
* ask_weather_location{"location": "Jamaica"}
    - utter_pleasant
* goodbye{}
    - utter_goodbye

## story 10
* greet{}
    - utter_greet
* ask_weather{"intent": "ask_weather"}
    - utter_ask_location
* ask_weather_location{"location": "dhaka"}
    - utter_pleasant
* ask_weather_location{"location": "Chittagong"}
    - utter_pleasant
* goodbye{}
    - utter_goodbye

## story 11
* greet{}
    - utter_greet
* ask_weather{"intent": "ask_weather"}
    - utter_ask_location
* ask_weather_location{"location": "hongkong"}
    - utter_pleasant
