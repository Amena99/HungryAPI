# Hungry? 
## A convenient app to find restaurants close to you that match your cuisine preference. 
### How to use the app: 
1. Open up the app by clicking the link [here](https://amena99.github.io/HungryAPI/).
2. Once you are on the site, click "allow" to allow Google to find your location. 
3. Next, enter a cuisine type. 
4. Hungry? will display a restaurant of that cuisine within 1.5 miles of where you are. Enjoy!
![alt text](https://i.imgur.com/OeQocnqm.png, "geolocation allow mssg") 
![alt text](https://i.imgur.com/MQm4hf5l.png, "search term") 
![alt text](https://i.imgur.com/8pdf7BKl.png, "search result") 

### My Contributions to Hungry?'s App Features
#### Incorporated Google Maps geolocation to find user location.
Used Google maps API to add geolocation to the site. When the user first lands on the page, they are prompted to allow the browser to find their location. Upon accept, the user's current latitude and longitude is tracked and parsed to use as a metric when searching for restaurants near them. 

![alt text](https://i.imgur.com/p6MMpMIl.png, "Google Geolocation Code")

#### Incorporated the Zomato API to find restaurants. 
The Zomato API provides data for restaurants across the globe with many searchable metrics including cuisine type. I used the Rapid API SDK to test and incorporate the Zomato API to use with this app. 

![alt text](https://i.imgur.com/86yaWs6l.png, "ZomatoAPI Code")
 

