# GPS-Position-Tracker


License of use:

-------------------------------------------
  Android Tracker
  Copyright (C) 2020 Android-Tracker

  This program is free software: you can redistribute it and/or modify
  it under the terms of the GNU General Public License as published by
  the Free Software Foundation, either version 3 of the License, or
  (at your option) any later version.

  This program is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  GNU General Public License for more details.

  You should have received a copy of the GNU General Public License
  along with this program.  If not, see <https://www.gnu.org/licenses/>.

--------------------------------------------


Information for installation:

You must have android studio for this app. You can download the latest version in this website:
https://developer.android.com/studio
After that, you can paste the code on your gradle and simulate the application in your computer through the build system. You must have a device simulator installed. You can do that through the app by clicking on the device manager. We recommend using the pixel 2 with the latest software.

Introduction

One of the drawbacks in public transportation in Morelia is the time wasted waiting for a vehicle to arrive. If there were a way to know when the next bus is arriving, we could make our systems more efficient. This is the motivation of our project.

Definition
We intend to set up a tracker for an android device.
A system that tracks the location of public transport units in real time.

General objectives
We will find the route that an android device has traversed while the app is on. We hope, eventually, it will help us develop a service to track our transportation system.

Methodology
Software Tools
We will use Android Studio to develop our application. The data will be retrieved either from a computer or another phone. It is important to note the system might have variation in performance depending on the android version

System Architecture
For this stage, we will get a phone to find its own location. The next stage will be to have it forecast that location to a computer or a phone. The final stage is to have it doing it periodically.

Data source
An android phone will be our only data source. It is important that it has signal and GPS services activated.
The data will be exported into a geoposition array, which will be interpreted into a map in the next stages.

Implementation
Check  java file and xml file
(IntelliJAmiya, StackOverflow)

Results

Test

Latitude: 19.731950
Longitude: -101.119380

Conclusions
The project is feasible and location services seem to have practical applications for our everyday lives. We hope to expand our range of application as much as possible.

Bibliography

IntelliJAmiya (2014), GPS Tracker cannot resolve in android studio. Retrieved on March 15 from: https://stackoverflow.com/questions/27637086/gpstracker-can-not-resolve-in-android-studio


Google Maps Plataform (2020), Location Data. Retrieved on March 15 from: https://developers.google.com/maps/documentation/android-sdk/location
