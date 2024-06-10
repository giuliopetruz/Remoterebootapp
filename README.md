# RemoteRebootApp

This project contains two Android applications:

1. **Server App**: An app installed on the device to be rebooted, listening for reboot commands.
2. **Client App**: An app that sends reboot commands to the server app.

## Server App

The server app listens on a specified port for incoming commands and reboots the device upon receiving a specific command. Root access is required.

## Client App

The client app sends a reboot command to the server app over the network.

### Features
- Reboot device remotely
- Requires root access for the server app

### Installation
1. Clone the repository: `git clone https://github.com/yourusername/RemoteRebootApp.git`
2. Open the project in Android Studio.
3. Build and run the server app on the target device.
4. Build and run the client app on any device.

### Contributing
Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

### License
[MIT](LICENSE)
