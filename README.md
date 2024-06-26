# MadTrain

## Workspace 
Github:  
- Repository: https://github.com/lauraszmigielska/MadTrain
- Releases:
  https://github.com/lauraszmigielska/MadTrain/tree/Class1
  https://github.com/lauraszmigielska/MadTrain/tree/Class2
  https://github.com/lauraszmigielska/MadTrain/tree/Class3
  https://github.com/lauraszmigielska/MadTrain/tree/Class4
  https://github.com/lauraszmigielska/MadTrain/tree/Class5

Workspace: https://upm365.sharepoint.com/sites/LauraSzmigielska/Documentos%20compartidos/Forms/AllItems.aspx?id=%2Fsites%2FLauraSzmigielska%2FDocumentos%20compartidos .  
  

## Description
The MadTrain is a mobile application designed to help users find the nearest Renfe train stations based on their current location. The app utilizes the GPS functionality of the device to determine the user's location and then calculates the distance to various Renfe stations.


## Screenshots and navigation

<table>
  <tr>
    <td>
      <img src="pagPrincipal.JPG" width="80%" alt="Pantalla principal en la que se calcula su ubicación actual"/>
      <p align="center">Pantalla principal en la que se calcula su ubicación actual</p>
    </td>
    <td>
      <img src="ubicaciónActual.JPG" width="80%" alt="Tu ubicación actual señalizada en el mapa"/>
      <p align="center">Tu ubicación actual señalizada en el mapa</p>
    </td>
  </tr>
  <tr>
    <td>
      <img src="estacionesRenfe.JPG" width="80%" alt="Las estaciones de renfe señalizadas en el mapa"/>
      <p align="center">Las estaciones de renfe señalizadas en el mapa</p>
    </td>
    <td>
      <img src="distancia.JPG" width="80%" alt="Distancia calculada"/>
      <p align="center">Distancia calculada</p>
    </td>
  </tr>
  <tr>
    <td>
      <img src="lista.JPG" width="80%" alt="Lista de estaciones Renfe"/>
      <p align="center">Lista de estaciones Renfe</p>
    </td>
    <td>
    </td>
  </tr>
</table>


## Demo Video
Video demonstrating how the app works (Max 1 video of 1 minute), upload it to a platform like YouTube or Vimeo (it might also work with Stream) and link it here:  
<a href="https://youtube.com/shorts/VtRtD-xNA2U?feature=share">
<img src="img/thumb.png" alt="Noise meter app" width="100" /> 
</a>


## Features
1 Location-Based Search: The app uses the device's GPS to pinpoint the user's current location.

2 Station Distance Calculation: It calculates the distance between the user's location and nearby Renfe train stations.

3 List of Renfe Stations: The app presents a list of Renfe stations.

4 Map View: Users can view the locations of nearby stations on a map for better visualization.

5 User Identifier: Users can optionally provide a unique identifier to personalize their experience.


## List the **technical** features of the app.
1 Persistence in CSV/Text File:
The app persists data related to user preferences and station information in CSV files for easy reading and writing operations.

2 Persistence in Shared Preferences:
User-specific settings such as theme preferences and last searched locations are stored using Shared Preferences.

3 Persistence in Room Database:
The app uses the Room database to store detailed information about Renfe stations, including names, coordinates, and other metadata.

4 Firebase Realtime Database:
For real-time updates and synchronization of user data across devices, Firebase Realtime Database is utilized.

5 Firebase Authentication:
The app employs Firebase Authentication to handle user sign-in and sign-up processes, ensuring secure access.

6 Maps: Google Maps Integration:
Google Maps API is integrated to display nearby Renfe stations on an interactive map, enhancing the user's navigation experience.

7 RESTful APIs Used:
The app uses OpenWeatherMap API to fetch real-time weather information for the user's current location, aiding in travel planning.

8 Menu: Toolbar:
A customizable toolbar menu is implemented for easy navigation and access to various app features.

9 Images: Glide Library:
The app uses the Glide library to efficiently load and display images, such as station photos and user avatars.

10 Sensors: GPS Coordinates:
GPS sensors are leveraged to obtain the user's current location, which is crucial for determining proximity to nearby Renfe stations.


## How to Use
Upon launching the app, users are prompted to grant location permissions.
Once permissions are granted, the app retrieves the user's current location using GPS.
In "Map" you can see your actual location and Renfe stations locations on the map, if you click on one of the stations you can see your distance to the station.
In "Collection" you have a list of the Renfe stations.


## Target Audience:

The Renfe Station Locator app caters to commuters, travelers, and tourists who rely on Renfe trains for transportation. It helps users quickly identify nearby stations, facilitating easier navigation and trip planning.


## Compatibility:

The app is designed for Android devices and is compatible with a wide range of smartphones and tablets running Android OS.


## Future Enhancements:

Future updates may include features such as real-time train schedules, notifications for service disruptions, and integration with other transportation services.


## Participants
List of MAD developers:
- Laura Szmigielska (laura.szmigielska@alumunos.upm.es) 

Workload distribution between members: Laura Szmigielska 100%

