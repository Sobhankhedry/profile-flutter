# Flutter Contact App

A simple Flutter app that allows users to make phone calls and send emails directly from the application. This app utilizes `url_launcher` to handle phone and email actions and demonstrates basic Flutter widgets like `TextField`, `CircleAvatar`, and `Column`.

## Features

- Make phone calls by entering a phone number
- Send emails by entering an email address
- Beautiful UI with profile picture and custom text styling using Google Fonts
- Input fields for phone and email with validation
- Supports sending emails with a predefined subject and body

## Screenshot

![image](https://github.com/user-attachments/assets/da3c8afa-5183-4db6-b46a-d8f4dfd176f2)


## Installation

### Prerequisites

Before running the app, make sure you have the following installed:

- Flutter SDK
- Dart SDK
- Android Studio or any other IDE with Flutter support

### Steps to Run the App

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/contact-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd contact-app
    ```

3. Install the necessary dependencies:
    ```bash
    flutter pub get
    ```

4. Run the app on an emulator or a physical device:
    ```bash
    flutter run
    ```

## Dependencies

The following dependencies are used in the project:

```yaml
dependencies:
  flutter:
    sdk: flutter
  url_launcher: latest_version
  google_fonts: latest_version
- `flutter`: The Flutter SDK to build and run the application.
- `url_launcher`: For launching phone calls and emails.
- `google_fonts`: To apply custom fonts from Google Fonts.
```
## Contribution Guidelines

We welcome contributions! If you'd like to contribute to this project, please follow the steps below:

1. **Fork** the repository to your own GitHub account.
    
2. **Clone** the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/contact-app.git
    ```

3. **Create a feature branch** for your changes:
    ```bash
    git checkout -b feature-name
    ```

4. **Commit your changes** with a descriptive message:
    ```bash
    git commit -m 'Add feature'
    ```

5. **Push** the changes to your branch:
    ```bash
    git push origin feature-name
    ```

6. **Open a Pull Request** on GitHub.

We will review the pull request and merge it if everything looks good. Make sure to follow the code style and provide a detailed description of the changes you made.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

**Sobhan Khedry**  


## Acknowledgements

- [Flutter](https://flutter.dev/) - The framework used to build this application.
- [url_launcher](https://pub.dev/packages/url_launcher) - For launching phone calls and emails.
- [Google Fonts](https://fonts.google.com/) - For providing beautiful fonts to improve the UI.
- [Icons8](https://icons8.com/) - For the icons used in the app.
