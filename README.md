# EC500-Full-Edition-P2PChat
     In this project, I
     Using socket Library and UDP protocal for communication 
     Using multiple threads: One thread for sending message, one thread for receiving message, 
     one thread for the Command line Interface
     design a simple communication protocal
     only use standard libraries such as socket, threading, os and so on
# Run Server:
    Please run the following codes:
    python server.py
    
# Run Client:
    python client.py  [username] [port]
          Example:  python client.py Dog 42001
                    python client.py Cat 42002
    PORT 42000 is used by server
     
## Feature of this P2PChat:
##### 1. Command Line System
![image](https://github.com/NESSESS/EC500-Full-Edition-P2PChat/blob/main/DemoPictures/command_line.PNG)
     People can use the command line to control the system, we have following commands:
     SET PUBLIC  - make you visible by other users
     SET PRIVATE - hide yourself
     CHAT [target] - Chat with a user and build a session, the user must be "PUBLIC" or in your friendlist
     !DIS!   Quit the chat session 
     LIST ONLINE - show all online users
     LIST FRIENDS - show all your friends
     LIST APPLY - show the friend applications from others
     ADD [target] Add someome online as friend
     CONFIRM [target] Confirm someone's friend application

     
##### 2. User friendly interface
![image]https://github.com/NESSESS/EC500-Full-Edition-P2PChat/blob/main/DemoPictures/Interface.PNG

##### 3. Message Notificatoin
![imgae](https://github.com/NESSESS/EC500-Full-Edition-P2PChat/blob/main/DemoPictures/notification.PNG)




##### 4. Chat Record
![image](https://github.com/NESSESS/EC500-Full-Edition-P2PChat/blob/main/DemoPictures/chat_record.PNG)

##### 5. Add Friends
   ![image](https://github.com/NESSESS/EC500-Full-Edition-P2PChat/blob/main/DemoPictures/FriendApply1.PNG)

##### 6. Chat with Friends with out server.

   

  
