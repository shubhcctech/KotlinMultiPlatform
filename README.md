# KotlinMultiPlatform
This is a Kotlin Multiplatform project targeting Android, iOS.

* `/composeApp` is for code that will be shared across your Compose Multiplatform applications.
  It contains several subfolders:
  - `commonMain` is for code that’s common for all targets.
  - Other folders are for Kotlin code that will be compiled for only the platform indicated in the folder name.
    For example, if you want to use Apple’s CoreCrypto for the iOS part of your Kotlin app,
    `iosMain` would be the right folder for such calls.

* `/iosApp` contains iOS applications. Even if you’re sharing your UI with Compose Multiplatform, 
  you need this entry point for your iOS app. This is also where you should add SwiftUI code for your project.

* `/shared` is for the code that will be shared between all targets in the project.
  The most important subfolder is `commonMain`. If preferred, you can add code to the platform-specific folders here too.


Learn more about [Kotlin Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html)…# MultiPlatformKotlin


# Kotlin Multiplatform Project: SpaceX Rocket Launch Tracker

This Kotlin Multiplatform project utilizes the SpaceX API to fetch information about successful rocket launches. Additionally, it calculates the number of days remaining until the next New Year.

## Features

- **SpaceX Rocket Launch Information**: Fetches successful rocket launch data from the SpaceX API.
- **Countdown to New Year**: Calculates and displays the number of days remaining until the next New Year.

## Requirements

- Kotlin Multiplatform setup
- Access to the SpaceX API

## Installation

1. Clone the repository:

    ```bash
    git clone [https://github.com/your_username/your_project.git](https://github.com/shubhcctech/KotlinMultiPlatform.git)
    ```

2. Set up the project dependencies and configurations.

3. Obtain an API key from the SpaceX API.

4. Place the API key in the appropriate configuration file.

## Usage

1. Run the project.

2. The application will fetch data from the SpaceX API and display information about successful rocket launches.

3. Additionally, it will show the countdown to the next New Year.

## Configuration

Ensure that your project is configured properly for Kotlin Multiplatform development. You may need to set up platform-specific configurations depending on your target platforms.

### SpaceX API Key

You need to obtain an API key from the SpaceX API. Once obtained, place the API key in the configuration file.

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to SpaceX for providing the API.
- Inspired by the countdown to New Year feature from various applications.

## About

This project is created and maintained by [Your Name]. For any questions or inquiries, please contact [shubham.kurkute@cctech.co.in].

Happy coding!

