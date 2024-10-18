# BluetoothIOT-App

This Android application, developed in Kotlin, utilizes Jetpack Compose for building the UI. The app incorporates features such as retrieving data from the Cosmo API, detailed device information screens, Bluetooth device discovery, and more.

<br>
Features
API Connection: <br>
Retrieve data from the Cosmo API's devices endpoint.
Detailed Device Information:
Each list item opens a new screen with detailed information about the selected device.
Bluetooth Device Discovery:
Detect nearby Bluetooth devices.
Connect to Bluetooth devices and display discovered characteristics.
User Interface Design:
Designed with creativity to provide an engaging and user-friendly experience.
<br>
Architecture
The app follows the MVVM architecture with clean architecture principles, including use of useCases and repositories.

MVVM Architecture:
The app is structured using the Model-View-ViewModel (MVVM) architectural pattern for a clear separation of concerns.
Clean Architecture Features:
UseCases: Centralized business logic in use cases.
Repositories: Data source abstraction for fetching data.
<br>
Tech Stack
Jetpack Compose: Modern Android UI toolkit for building native UIs.
Hilt: Dependency injection framework for Android.
Coroutines: For handling asynchronous tasks and flows.
Espresso and JUnit: Used for unit and instrumented testing.
<br>
Bluetooth Communication
GATT (Generic Attribute Profile):
The app utilizes GATT for communication between Bluetooth or IoT devices.
GATT defines a hierarchical data structure and set of procedures, providing a framework for discovering services and characteristics on Bluetooth Low Energy (BLE) devices.
<br>
Dependencies
Compose Libraries:
androidx.compose.ui
androidx.compose.ui:ui-tooling
androidx.compose.material3
Dependency Injection:
Hilt for Android.
Networking:
Retrofit for API communication.
Gson for JSON serialization.
Bluetooth Communication:
GATT for Bluetooth communication.
