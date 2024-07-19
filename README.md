## Buddy Alert - Proximity Alert App

**Buddy Alert** is a web application that allows you to track the location of a designated "buddy" in real-time and receive an alert when they come within a close proximity of you. This app is ideal for situations where you want to ensure the safety of someone you're with, such as going for a run in unfamiliar territory or attending a crowded event.

**Features:**

* Real-time location tracking of your designated buddy on a map.
* Proximity alert that notifies you when your buddy comes within a set distance (default: 10 meters).
* Utilizes Google Maps API for location visualization.
* Firebase integration for storing and syncing user locations.

**Requirements:**

* A web browser with JavaScript enabled.
* A smartphone with an active internet connection and geolocation enabled (for both you and your buddy).
* A Firebase project with a working Realtime Database.  You can follow the instructions on [https://firebase.google.com/](https://firebase.google.com/) to set up a Firebase project.

**Setup:**

1. Replace the placeholder API key (`AIzaSyDi2405-IdGAtYjDM8i0m-NdHEAE-zEfFI`) in the code with your own Google Maps API key. You can obtain a free API key by creating a project on [https://console.cloud.google.com/](https://console.cloud.google.com/).
2. Update the `userId` and `otherUserId` variables in the code with your unique identifiers and your buddy's identifier.

**Usage:**

1. Open the app in your web browser on both your and your buddy's devices.
2. Grant the app location permissions when prompted on each device.
3. The app will automatically display your and your buddy's locations on a map, assuming geolocation is enabled on both devices.
4. You will receive an alert whenever your buddy comes within 10 meters of your location (this distance can be customized in the code).

**Note:**

* This is a basic implementation and does not include any user authentication or authorization features.
* You should share your unique user ID with your buddy so they can track your location as well.
* Be mindful of battery usage as continuous location tracking can drain battery life.

**Further Development:**

* Implement user authentication and authorization for secure location sharing.
* Allow users to set custom proximity alerts.
* Integrate messaging functionality for communication between users.
