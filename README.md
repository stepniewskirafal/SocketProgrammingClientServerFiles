# Socket Programming

## Description
Socket Programming is a client/server application that enables data transfer using sockets. The program is designed to facilitate user management and message handling.

## User Management
The application provides functionalities for user creation and login. Users can send and check received messages, as well as clear their inbox. Additionally, administrators have the privilege to delete users or grant them special privileges.

## Message Management
The application allows users to send private messages to other users, with a maximum limit of 255 characters per message. Users have an unread messages box that can store up to 5 messages, while the admin inbox has unlimited capacity. When the inbox is full, the sender is notified of the overflow.

## JSON File Format
The application uses JSON file format to store user and message information. This format allows for easy parsing and manipulation of data.

## Commands

### For Admin:
- `uptime`: Returns the server's running time.
- `info`: Returns the server version and creation date.
- `help`: Displays a list of available commands.
- `stop`: Stops the server and client.

- `listAllUsers`: Shows a list of all users and their roles.
- `addNewUser`: Adds a new user to the application.
- `deleteUser`: Deletes a user from the application.
- `sendMessage`: Sends a message to another user.
- `readMessage`: Reads the chosen message.

### For Regular User:
- `sendMessage`: Sends a message to another user.
- `readMessage`: Reads the chosen message.
- `stop`: Stops the server and client.
