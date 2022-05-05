# Assignment

## Build a weather app

For this assignment please use the **tech stack** requested in the email that was sent to you.
If no tech stack was defined, we would suggest to use [**React**](https://reactjs.org/) coupled with [**Redux**](https://redux.js.org/).

### **PART I**
Using the [OpenWeatherMap API](https://openweathermap.org/api) we want you to create a page where the current weather will be displayed as well as the forecast for the next 7 days. For the current weather, we want you to get the user's location and get the weather from that location (in case you can’t fetch the location of the user, then use these coords for Leiria [39.74362, -8.80705]). The same is valid for the forecast data.

The current weather and the forecast data must display an icon corresponding to the type of weather (this is valid for part I and part II).

To solve this problem, there is no need for user authentication.

### API KEY
If you do not have an OpenWeatherMap API key, create one for free. All the services you need are free of charge.
To get the API key, go to https://openweathermap.org/price and then you'll be able to get a key for `Current weather and forecasts collection` under the free section.

Relevant pages to check the API are:
- https://openweathermap.org/current
- https://openweathermap.org/api/one-call-api

### **PART II**
On this part we want you to add a bit more complexity to the application.
After this part is concluded, the user should be able to:

- Add a city (with country) in order to check the weather in different places
- Remove a city from that list
- Get current weather from any added city
- Get 7 day weather forecast for any added city
- Persist the cities that are added by the user (along with the country)
- Give feedback to the user in every relevant operation he does

## Evaluation

We will discuss the project from a few different points:

**Architecture**. You’re welcome to organize the code in a way that you believe suits best. Here, we’ll discuss possible alternatives and exchange a few ideas

**Engineering**. We’ll discuss this point based on the actual code: how it’s organized and written, if it’s easy to get picked up by a new engineer in a team (or in community, if we talk about open source). Of course it’s important that the code is readable, but we’ll go beyond that and talk about coherence of the codebase and its hypothetical (or potential) future.

**Tooling**. How does a completely unfamiliar user with basic technical background get the code and run it? What programs are expected to be available on user’s computer before installing the tool? How could that user potentially do a micro-deploy on their own machine?

**Documentation**. Good code is one that documents itself, but sometimes it isn’t enough. We’ll discuss things such as quick start guide, code style and contribution guideline. It’s important that a new team member that joins the team and gets introduced to the codebase, or another team that develops integration, has a really good time exploring the code.
