# UfoChat - Chat App with Java Sockets

UfoChat is a simple chat application developed in Java that utilizes sockets for real-time communication. It provides a user-friendly interface with support for emojis and is built using JavaFX and the JFoenix library. This project is designed to help you understand socket programming and GUI development in Java.

## Table of Contents

- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Dependencies

UfoChat uses the following dependencies, which are managed through Maven:

- **JavaFX**: JavaFX is used for creating the graphical user interface (GUI).
  - Group ID: org.openjfx
  - Artifact ID: javafx-fxml
  - Version: 18.0.2

- **JFoenix**: JFoenix provides material design components for JavaFX applications, enhancing the UI.
  - Group ID: com.jfoenix
  - Artifact ID: jfoenix
  - Version: 9.0.1

- **Emoji-Java**: This library allows you to handle emojis in your chat application.
  - Group ID: com.vdurmont
  - Artifact ID: emoji-java
  - Version: 5.1.1

## Usage

To run UfoChat, follow these steps:

1. Clone this repository to your local machine.

2. Open the project in your favorite Java IDE, such as IntelliJ IDEA or Eclipse.

3. Build the project using Maven to download the dependencies:

   ```shell
   mvn clean install
4.Run the Main class located in org.example.ufochat package.
5.The UfoChat application will launch. You can now start chatting with others using this simple chat application.

## Contributing
Contributions are welcome! If you'd like to improve UfoChat or add new features, please create a pull request with your changes.

## License
This project is licensed under the MIT License.
