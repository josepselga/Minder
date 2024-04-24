![Minder](/images/minder.png)

_Model–view–controller (MVC) Project_

* Java Client-Server
* MySQL Database

Project Structure:
Minder Server: https://github.com/josepselga/Minder_Server
Minder Client: https://github.com/josepselga/Minder_Client
Minder Database: https://github.com/josepselga/Minder_Database

Video: https://youtu.be/Vv5N63C0tBM

**Ask for access to Minder's private development repositories**

The project we are going to carry out is called "Minder", and it is a program very similar to the current application called "Tinder" and will follow a Client-Server structure.
The first function that the Client includes is to log in, if he has already registered previously, and in case he has not done so, he also includes the function in order to register within the platform.
The second function that the Client includes is to edit the information of his profile. Information such as your photograph, your description, your tastes…
The next function of the client is to accept or discard other users of the platform, which will be displayed through the main window.
In case the user has a like in common with another user, a "match" will take place, which will be added to the list of "matches" of the user, with whom he can either chat or delete the "match". match ”.
Finally, the client also includes the logout function, a function that the user can perform at any time.

On the other hand, the server will have other features to implement. The first function of the server will be to register or authenticate a user, depending on whether they have previously registered or not.
The second function required to implement the server is to manage the profiles of users registered on the platform and synchronize them in real time with each other.
The next function will be to manage matches and chats between users, and as with the previous function, it will also have to be done in real time, this means that the data will have to be updated whenever there is any type. of modification in these, and not every so often.
The last two functions of the server must be through its graphical interface, and these are the functions of showing the evolution of the matches over time and the function of showing the 5 most accepted users of the platform.
In order to perform some of these functions, the Server will have a connection to a database where the information is stored. The client will never have direct access to this database, so it will always have to go through the server.

It should be noted that the program must be able to support multiple connected clients simultaneously and that both client and server information must be updated in real time.

# Images

* Client

<br />

![Minder Client Login](/images/client-login.png)
![Minder Client Register](/images/client-register.png)
![Minder Client Principal](/images/client-prin.png)
![Minder Client Chat](/images/chat.png)

* Server

<br />

![Minder Server Principal](/images/server-principal.png)
![Minder Server Stats 1](/images/server-stat1.png)
![Minder Server Stats 2](/images/server-stat2.png)
