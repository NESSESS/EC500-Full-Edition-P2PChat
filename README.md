# EC500-Full-Edition-P2PChat
     In this project, I
     Using socket Library and UDP protocal for communication 
     Using multiple threads: 
          One thread for sending message, one thread for receiving message, 
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
![image](https://github.com/NESSESS/EC500-Full-Edition-P2PChat/blob/main/DemoPictures/Interface.PNG)

##### 3. Message Notificatoin
![imgae](https://github.com/NESSESS/EC500-Full-Edition-P2PChat/blob/main/DemoPictures/notification.PNG)


##### 4. Chat Record
![image](https://github.com/NESSESS/EC500-Full-Edition-P2PChat/blob/main/DemoPictures/chat_record.PNG)

##### 5. Add Friends
![image](https://github.com/NESSESS/EC500-Full-Edition-P2PChat/blob/main/DemoPictures/FriendApply1.PNG)
        
     Using ADD [target] to add a user as a friend. The target user  must be in public state.
     Using LIST APPLY to see the pending application from others.
     Using COMFIRM [target] to add sb as friend.
     using LIST FRIENDS  to see your friends.

##### 6. Hide themselves
     If one user want to be found by others, he can run "SET PUBLIC"
          In public state, he can chat with his friends or other users who are in public state
     If one want to hide himself, he can run "SET PRIVATE"
          In private state, people can still chat with his friends.


   

  
