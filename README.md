# Location spoofing
Location spoofing is a form of interference which makes the receiver believe, user is at a false location. It is the act of faking or manipulating the GPS coordinates of a device and is helpful as a user can spoof their current location and be at a spoofed location.

## Need for location spoofing
The main purpose of location spoofing in testing is to create several situations and places in order to assess how a service or application performs under various circumstances.

## Geo Location
Geolocation refers to the use of location technologies such as GPS or IP addresses to identify and track the whereabouts of connected electronic devices. Geolocation is frequently used to track people's movements and locations as well as for surveillance purposes because people frequently carry these devices.

## Geolocation Testing
Geolocation testing checks your application in different geographic locations to ensure that it meets all  legal requirements related to those locations and  works as expected regardless of location. This includes checking the validity of the application in each geographic location where it may be used. Check the application  efficiency and performance of IP in various locations.

## Location Spoofing in Android
## Fake GPS App
Fake GPS is a reliable and convenient best fake location app. In only a few clicks, you can choose your ideal place from all over the world as it supports multiple locations, the Fake GPS app allows you to choose a location anywhere in the world. 

## Steps to spoof location
1. Install the app from <a href="https://play.google.com/store/apps/details?id=com.lexa.fakegps&hl=en&gl=US">play store</a>.
<figure>
    <img src="/Images/ImageFG1.png" width="150" height="200"
         alt="App Installation">
</figure>
2. Open the app.
<figure>
    <img src="/Images/ImageFG2.png" width="150" height="200"
         alt="App Launch">
</figure>
3. Tap on ellipsis on top right corner.
<figure>
    <img src="/Images/ImageFG3.png" width="150" height="200"
         alt="App options">
</figure>
4. Tap on Search.<br/>5. Enter the coordinates.
<figure>
    <img src="/Images/ImageFG5.png" width="150" height="200"
         alt="Enter coordinates">
</figure>
6. Set the mock location in Developer option by selecting "Fake GPS" app in Select mock location app option.
<figure>
    <img src="/Images/ImageFG6-1.png" width="150" height="200"
         alt="Allow Mock Location 1">
</figure>
<figure>
    <img src="/Images/ImageFG6-2.png" width="150" height="200"
         alt="Allow Mock Location 2">
</figure>
<figure>
    <img src="/Images/ImageFG6-3.png" width="150" height="200"
         alt="Allow Mock Location 3">
</figure>
7. Tap on play icon in menu bar when you want to start.
<figure>
    <img src="/Images/ImageFG7.png" width="150" height="200"
         alt="Start mocking">
</figure>
8. Tap on pause icon in menu bar when you want to stop.
<figure>
    <img src="/Images/ImageFG8.png" width="150" height="200"
         alt="Stop mocking">
</figure>

## Location spoofing in iOS
In iOS, it is a bit tricky to spoof locations so developers provide an option in development builds to enter coordinates from app settings or select locations from list which can be used to mock location programatically.

## Steps
1. Install the app.
2. Open app settings from native iOS Settings app.
<figure>
    <img src="/Images/ImageiOS1.png" width="250" height="200"
         alt="iOS native app settings">
</figure>
3. You will find an option to enter coordinates(If added by developer).
<figure>
    <img src="/Images/ImageiOS.png" width="250" height="200"
         alt="iOS Mock Location">
</figure>
4. Save the values entered and on launching app now, you can see mocked location. 

## Location spoofing using <a href="https://www.browserstack.com/docs/app-live/location-testing/geolocation-testing">Browserstack App Live</a>
Location can be changed using Browserstack in both Android and iOS devices.
Steps to change location:
1. Click on Change location.
<figure>
    <img src="/Images/ImageBS1.png" width="250" height="200"
         alt="Browserstack 1">
</figure>
2. Enter the latitude and longitude.
<figure>
    <img src="/Images/ImageBS2.png" width="250" height="200"
         alt="Browserstack 2">
</figure>
3. Confirm the location by clicking on Yes.
<figure>
    <img src="/Images/ImageBS3.png" width="250" height="200"
         alt="Browserstack 3">
</figure>

## Example of spoofing location for testing

We did perform location spoofing for testing an adventure park mobile application to mimic different behaviours such as user being at the park or when user is away from the park.
For testing such scenarios, we used the above described approach for testing.

A realtime scenario where location spoofing was needed is in food ordering.
Our app had a module wherein the user could place food order from mobile app only if they are at the park else the user can browse through restaurants and menu but cannot place order. 

To test placing food orders from different locations and restaurants, we had to spoof our location and ensure the functionality is working as intended.