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
The Zomato API provides data for restaurants across the globe with many searchable metrics including cuisine type. I used the Rapid API SDK to test and incorporate the Zomato API to use with this app. The main search metrics are cuisine type, the latitude and longitude of the user (obtained through geolocation) and the distance radius. Zomato returns hundreds of results as the radius is increased. I set the radius to 1000 meters, a reasonable walking distance for users. The results were then further limited to the first 20, and a random number was generated to select one of them to display to the user. The user display contains only one restaurant to stay true to our concept of an app that provides a no-hassle, no-decision solution to eating out for a certain cuisine type. However, if the user cannot accept the displayed choice, they may click the 'Search' button again to display another restaurant from the API results. 

![alt text](https://i.imgur.com/86yaWs6l.png, "ZomatoAPI Code")
 

