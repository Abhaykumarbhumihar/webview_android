# WebView Example Application

This Android project demonstrates the use of a `WebView` to load a webpage within an Android app. The app includes basic functionality such as loading a URL, enabling JavaScript, handling offline scenarios, and providing navigation features.

## Features

- **WebView Integration**: Loads a webpage inside the app without opening an external browser.
- **JavaScript Support**: JavaScript is enabled for interactive content in the WebView.
- **Offline Handling**: Displays a custom "No Internet Connection" message when there is no active internet connection.
- **Web Navigation**: Users can navigate back through web history inside the WebView.
- **Responsive WebView**: Supports scaling and pinch-to-zoom with built-in zoom controls.

## Project Structure

```bash
.
├── app
│   ├── src/main
│   │   ├── java/com/zumamobile/MainActivity.kt    # MainActivity class with WebView functionality
│   │   ├── res
│   │   │   ├── layout/activity_main.xml           # Layout file containing WebView
│   │   │   └── values
│   │   │       └── strings.xml                    # String resources
│   └── AndroidManifest.xml                        # Application manifest file
