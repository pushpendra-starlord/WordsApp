# WordsApp
This app demonstrate the usage of Room persistance library for storing data locally in device.

## Implementation
### Data Layer
The database is created using Room and has one entity: Word. Room generates the corresponding SQLite table at runtime.
Queries are executed in the WordDao class. The word retrieval is done via an observable query implemented using a LiveData. 

### Presentation Layer
The app has a main Activity that displays the data. The Activity works with a ViewModel which fetches data from room database through repository class
and passes the data to UI class (MainActivity).

### Architecture
![App Architecture](https://codelabs.developers.google.com/codelabs/android-training-livedata-viewmodel/img/1205d9f95688b35b.png)

## Installation
Clone the project in Android Studio or simply download the zip file.

## Screenshots
![Main Activity](https://codelabs.developers.google.com/codelabs/android-training-livedata-viewmodel/img/f79b6d29612488b2.png)          ![New Word Activity](https://codelabs.developers.google.com/codelabs/android-training-livedata-viewmodel/img/9f96622d49695bd5.png)

## Download APK
To test the app directly on your phone download and install app from below link.
[Download apk file](https://drive.google.com/file/d/10A-VsOBsCPY8XNqjPE5ZEhyqrrbsHTKr/view?usp=sharing)
