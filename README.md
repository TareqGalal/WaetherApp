
# **WeatherApp Project**



## **. Project Overview**

**WeatherApp** is a desktop application developed using **JavaFX** and **Java 17+**. The application enables users to input a city name and retrieve real-time weather information via an external weather API. Designed with a clean, intuitive user interface, the app serves as a demonstration of how to integrate third-party API data into a modern JavaFX desktop application.



## **. Objectives**

The main objectives of the WeatherApp project are:

* To design an interactive and responsive graphical user interface using JavaFX.
* To enable users to search for and retrieve live weather data based on city names.
* To display essential weather metrics, including:

  * **Temperature**
  * **Humidity**
  * **Weather Description**
* To apply object-oriented programming (OOP) principles in structuring and organizing code.



## **. Technologies Used**

The development of WeatherApp incorporates the following technologies and tools:

* **Java 17+** – Core programming language
* **JavaFX** – Used for designing and managing the GUI
* **Maven** – For build automation and dependency management
* **IntelliJ IDEA** – Integrated Development Environment (IDE)
* **OpenWeatherMap API** (or similar) – For fetching real-time weather data
* **JSON** – For parsing and managing API response data



## **. Application Structure**

The application follows a modular **Model-View-Controller (MVC)** architecture:

* **WeatherApp.java**

  * Entry point of the application; initializes and launches the primary stage.

* **WeatherController.java**

  * Handles user input and manages the logic for fetching and displaying data.

* **WeatherService.java**

  * Performs API requests and processes the JSON responses to extract weather details.

* **weather.fxml**

  * The FXML layout file that defines the structure of the graphical user interface.



## **. Key Features**

The WeatherApp offers the following core functionalities:

* **Live City Search:** Users can enter any valid city name to get real-time weather updates.
* **API Integration:** Robust integration with a weather API, complete with error handling for invalid input or network issues.
* **User-Friendly Interface:** Simple and clean UI ensures a smooth user experience.
* **Modular Design:** Follows the MVC pattern to ensure maintainability and scalability.
* 

## **. Future Enhancements**

To further improve the application, the following features are proposed for future development:

* **Forecast Extension:** Provide weather forecasts for the next few days.
* **UI Enhancements:** Integrate animations, theme customization, or a dark mode for improved UX.
* **Unit Testing:** Implement automated tests for the service and controller layers to ensure code reliability and maintainability.




