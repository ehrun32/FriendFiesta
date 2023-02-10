# FriendFiesta 

*Need A Friend??* 😔 
<p> HOP ON FRIEND FIESTA 😉 </p>

 

## Project Summary
FriendFiesta is a messenger application designed for users to join chatrooms and engage in real-time conversations with strangers. The app will be developed using Python and a combination of the socket.io, flask, SQL and flask-socketio frameworks. The users will have the option to join a chatroom with a unique name and engage in immediate, seamless conversations with others. Another benefit of the app is that users can access the history of previous conversations and review past messages..

## Requirements
Make sure to install the required framworks for this applciation, also need python 3.6+ for this project to work
<p>
flask
</p>
<p>
flask-socketio
</p>
<p>
eventlet
</p>
<p>
python-dotenv
</p>

## Run
Click on the main.py file and just run this file on your localhost network and open your localhost network.

## Implementation
### Socket.IO
- Socket.IO is a communication protocol that allows for real-time, two-way event-based interactions between clients and servers. Typically, clients are web browsers but they don't have to be. The standard client and server components are written in JavaScript.
### Flask
- Flask is a lightweight web framework for Python that is considered a "microframework." This is because it does not include any specific tools or libraries and is minimal in its design. It lacks a database abstraction layer, form validation, and other components that are commonly provided by third-party libraries. Flask's simplicity allows developers to build small, specific applications without being weighed down by unnecessary features.
### flask-socketio
- Socket.IO integration for Flask applications. It is built over python-socketio which provides Python implementations of a Socket.IO client and server.

## File Explanation
### main.py
- Calls the whole appilcation and start the web server

### __init.py__
- This file creates a new flask appication and import the necessary module.

### database.py

- Works as an sqlite database, it makes a table, closes a connection, creates a table just some basic query with SQL. 
- We will take the message by the date and time and returns it in a JSON format.
- This will store all the messages.

### views.py
- This is wher all the routes, login, history and signout.

### filter.py
- A custom slice filter.

### config.py
- necessary requirements for the webserver.

## Flow of events

<p align="center">
  <img src="https://user-images.githubusercontent.com/57046416/218004364-bc0aa996-ca65-484c-a882-2fe2a7a1f99f.png"/>
</p>

## Prototype
The following section discusses the performance of the integrated prototype as a whole. The
prototype is completely functional and all promised features have been delivered. 

### Web Application/Server
The final web application design along with its implemented features are shown below.




<p align="center">
  <img src="https://user-images.githubusercontent.com/57046416/218005418-d7e4e142-3021-4854-8037-0f29f04f367f.png"/>
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/57046416/218004515-6c9a41e1-d080-4e49-adcd-1322321416a0.png"/>
</p>



## Next steps

Things to improve:
- Make the app scalable with a lot of users
- Make the app have a password for loggin in



## References

- https://socket.io/
- https://python-socketio.readthedocs.io/en/latest/


