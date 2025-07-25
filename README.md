A Kotlin Android application using Skyscanner's Backpack UI components to display flight information.
Complete Setup Guide
1. Create New Project in Android Studio

Open Android Studio
Click "New Project"
Choose "Empty Activity" template in Phone and Tablet section
Configure your project:

Name: FlightInfoApp (or your choice)
Language: Kotlin
Minimum SDK: API 33: Android Tiramisu
Package name: Will be auto-generated


Click "Finish"

2. Add Backpack Dependency

Wait for project initialization to complete
Open app/build.gradle (Module: app) from Gradle Scripts
Add Backpack dependency to dependencies block
Click "Sync Now" when prompted

3. Replace Files
Replace/create these files with the content from the artifacts below:

app/src/main/res/layout/activity_main.xml
app/src/main/java/com/yourpackage/flightinfoapp/MainActivity.kt
app/src/main/res/values/strings.xml
app/build.gradle (Module: app)

4. Run the Application

Click the green arrow (Run) button
Wait for the emulator to launch
Your flight information app should appear

5. UI Features Implemented
✅ Flight Information Card: Displays flight number "SK 1234"
✅ Departure Card: Shows "LHR" airport code and "14:30" departure time
✅ Arrival Card: Shows "JFK" airport code and "18:45" arrival time
✅ Flight Details Card: Additional information like duration and aircraft
✅ Large corner style on all BpkCardView components
✅ Proper BpkText styling with different heading levels
