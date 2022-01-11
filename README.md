![image](https://user-images.githubusercontent.com/97542292/149010251-c6d1d3e9-2ab9-49f9-84a8-72e7a09b51a4.png)

# SAFE Labs Backend Challenge

## Presentation

Hello there SAFE Labs Candidates!

To better assess your technical skills, we prepared this small challenge as part of our hiring process.

## The Challenge

Create a micro-service able to accept RESTful requests receiving as parameter
either city name or lat long coordinates and returns a playlist (only track
names is fine) suggestion according to the current temperature.

## Business rules

* If temperature (celcius) is above 30 degrees, suggest tracks for party
* In case temperature is between 15 and 30 degrees, suggest pop music tracks
* If it's a bit chilly (between 10 and 14 degrees), suggest rock music tracks
* Otherwise, if it's freezing outside, suggests classical music tracks 

## Hints

You can make usage of OpenWeatherMaps API (https://openweathermap.org) to fetch
temperature data and Spotify (https://developer.spotify.com) to suggest the
tracks as part of the playlist.

- [Spotify API](https://developer.spotify.com/documentation/web-api/quick-start/) (You can use this Client Id: 08c1a6be652e4fdca07f1815bfd167e4)
- [OpenWeatherMaps API](https://home.openweathermap.org/users/sign_up) (You can use this API Key: b77e07f479efe92156376a8b07640ced)

### Sample cities
http://api.openweathermap.org/data/2.5/weather?q=campinas&appid=b77e07f479efe92156376a8b07640ced
http://api.openweathermap.org/data/2.5/weather?q=salvador&appid=b77e07f479efe92156376a8b07640ced
http://api.openweathermap.org/data/2.5/weather?q=brasilia&appid=b77e07f479efe92156376a8b07640ced
http://api.openweathermap.org/data/2.5/weather?q=fortaleza&appid=b77e07f479efe92156376a8b07640ced
http://api.openweathermap.org/data/2.5/weather?q=manaus&appid=b77e07f479efe92156376a8b07640ced

## Non functional requirements

As this service will be a worldwide success, it must be prepared to be fault
tolerant, responsive and resilient.

Use whatever language, tools and frameworks you feel comfortable to, and
briefly elaborate on your solution, architecture details, choice of patterns
and frameworks.

Also, make it easy to deploy/run your service(s) locally (consider using some
container/vm solution for this). Once done, share your code with us.

## Deliverables

The deliverable for this challenge is the code, inside a public GitHub repository of yours. You should provide us the URL for it.

We should be able to run your application on our computers, and your README should have all the information necessary for it. 

Send us a report telling how was your experience with this challenge. Even if you can't finish, send the report because for us is more important to know your dedication on a project, thinking, and analytical skills, than looking only at your technical skills.

We will evaluate you based on how well the system is architected, your code and tooling practices, your instructions and documentation on the README.MD and how well you defend your idea and decisions when presenting it to us.

## Questions?

If you have any questions, please send an email to your contact at SAFE Labs that we will reply as fast as we can :)
