# Weight-Tracking-App
## Overview
This is a `fully developed user-focused Android app` that allows users to track their weight over time and set a goal weight to receive a notification. The app was created to be a convenient way for `users to achieve their goals`, no matter where they are. The app consists of `three screens`: one to log in and sign up, one for the main display, and a settings page. The database for our app has three tables: one for user logins, one for user weights and their respective dates, and one for user goal weights. These tables are all connected via the user_id created in the login table. **I hope to build upon this app in the future**

### Main Display Screen
<img alt="Picture of Main Display Screen" src="https://github.com/crestongetz/Weight-Tracking-App/blob/464a8035285badcfe85176fc734c654dad556321/Pictures/Weight%20Tracker%20Main%20Display.png"/>

## Getting Started
You will need the following:
1. [Java](https://www.oracle.com/java/technologies/downloads/)
2. [Android Studio](https://developer.android.com/studio)
3. A dedicated GPU(recommended not required)

### How to Run
1. Download the [zip file](https://github.com/crestongetz/Weight-Tracking-App/blob/cb0d47adde13dcff5d0ccb6471078380f65d3865/Weight%20Tracking%20App.zip).
2. Extract the zip file.
3. If any `build/`, `.gradle`, or `.idea/` folders are present, you should delete them.
4. In Android Studio, select file -> open and open the folder directory
5. Once opened, let Gradle sync. If you run into issues, you may need to download plugins which requires a internet connection.
6. Create a device in the Device Manager or use a physical Android device connected via USB.
7. Once the device is connected, hit the Green Run or play button.

Note that if you are using the emulator `without a GPU`, it will be very slow. A `good integrated GPU` should work fine, but a dedicated one is ideal.

## Launch Plan
You can view the `plans to monetize` and `launch` the app here: [Launch Plan (PDF)](https://github.com/crestongetz/Weight-Tracking-App/blob/6b33a51977de6b867689ef2f9d62fe6c79c73a84/Files/Weight%20Tracking%20App%20Launch%20Plan%20PDF.pdf)

## Tools/Frameworks Used
- Java (JDK)
- Android Studio
- Android Jetpack
- SQL
- XML
- Gradle
- MVC

## Future Improvements
- Complete launch plan and publish app
- Montize app
- Add more features, such as charts and more advanced tracking
- Add the ability to track other metrics like body fat or height
- Add a social aspect to the app to allow users to add friends and support each other (MVP test first)


## Reflection
This app was designed to address the specific user need for a convenient way to track their weight over time. The `users we identified` were `athletes`, people seeking `general wellness`, people trying to `lose weight`, and `professionals`. We can tailor our store listings and advertising to test which of these groups may use the app the most. When creating the app, I needed to determine the bare minimum to avoid `over-engineering`. It would be better to add more based on user feedback than to create an app no one wants to use. The grid display used in this app keeps users in mind by allowing them to add, create, delete, or edit entries while enabling easy viewing. I tried not to overload the screen and keep the app very simple. Having a `UI-centered app` increases the likelihood that users will continue using it.

Many strategies were used in developing this app. The most important being a `focus on the user`. Putting yourself in the user's shoes is valuable, but it can only get you so far. I found that having `real people` test the app, `give feedback`, and then build upon that is a great way to improve functionality and add features. Another great strategy I have always used is testing my code frequently. After each change, I run it in the emulator to see whether I broke anything or could improve it. Doing this helps me learn what the code is actually doing much faster and ensures the code is functional. I plan to keep these strategies in mind, especially an increased focus on the user, in the future. I created a thorough plan for the features I would need for the app's users, which not only helped me build what I needed but will also help the app make money. 

This was a unique challenge for me. This is the first mobile app I have built. One of the hardest features I built was the SMS notifications. I had to figure out a way to connect the database with the logic to send the SMS, only send it when the user wants it, ensure the app will still work when it's off, and ensure that if different users are using the same phone, their settings stay unique to them. My strongest part of this project was the planning and outlining I did. The planning phase proved helpful in accelerating my development process. By approaching the project with a `business-focused mindset`, I was able to identify clear use cases and evaluate the app's real-world use. Including how it could `generate value and revenue`. This stage of the project best highlights my ability to bridge technical implementation with strategic thinking, and reflects the skills and knowledge I have developed so far in my journey.


