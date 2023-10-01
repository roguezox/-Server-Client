# Server-Client Encryption and Decryption in Java

## Introduction

This README provides an overview and instructions for using a simple Server-Client application in Java that implements encryption and decryption for secure communication.

## Features

- Secure communication using encryption and decryption.
- Support for multiple clients connecting to the server simultaneously.
- Easy-to-use command-line interface.
- Customizable encryption and decryption algorithms.

## Prerequisites

Before using this application, make sure you have the following prerequisites installed:

- Java Development Kit (JDK) 8 or higher.
- A code editor or Integrated Development Environment (IDE) like Eclipse or IntelliJ IDEA.

## File Structure

```
src/
  └── main.java
  └── server.java
  └── client.java
```

## Usage

### Server

1. Open a terminal or command prompt.

2. Navigate to the `src` directory:

   ```bash
   cd src
   ```

3. Compile the Server.java file:

   ```bash
   javac server.java
   ```

4. Run the server:

   ```bash
   java server
   ```

   The server will start listening for incoming connections on the default port (8080). You can customize the port by providing it as an argument when running the server:

   ```bash
   java server <port>
   ```

### Client

1. Open a separate terminal or command prompt.

2. Navigate to the `src` directory:

   ```bash
   cd src
   ```

3. Compile the Client.java file:

   ```bash
   javac client.java
   ```

4. Run the client:

   ```bash
   java client
   ```

   The client will prompt you to enter the server's IP address and port number. Enter the server's details and start communicating securely.

## License

This Server-Client Encryption and Decryption code is open-source and available under the [MIT License](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt). You are free to use and modify it according to your requirements.

If you have any questions or encounter any issues, please feel free to [open an issue](https://github.com/roguezox/Server-Client/issues).
Happy coding!