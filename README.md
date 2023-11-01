# NTP Time Synchronization Android App

This Android application demonstrates how to synchronize the device's time with a Network Time Protocol (NTP) server and display the synchronized time. The app checks the internet connection, and if available, synchronizes the time with an NTP server; otherwise, it uses the system time.

## Features

- **NTP Time Synchronization:** The app synchronizes the device's time with an NTP server to ensure accurate timekeeping.
- **Internet Connection Check:** It checks the internet connection status before attempting NTP synchronization.
- **User Interface:** The synchronized time is displayed in a user-friendly format on the app's interface.

## Implementation Details

### Libraries Used

- [Apache Commons Net](https://commons.apache.org/proper/commons-net/): Utilized for NTP time synchronization.

### Code Structure

#### MainActivity.java

- **onCreate():** Initializes the app's UI components and sets up a handler to update the time every second.
- **UpdateTime():** Determines whether to use NTP-synchronized time or system time based on internet availability.
- **getNetworkTime():** Fetches the time from an NTP server and returns it as a `Date` object.
- **isNetworkAvailable():** Checks the device's internet connection status.

## Usage

1. Clone or download the repository.
2. Open the project in Android Studio.
3. Build and run the app on an Android emulator or a physical device.

## Requirements

- Android Studio 4.0+
- Android SDK with API level 21+


## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for your purposes.

---
