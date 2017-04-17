# Local-chat-usying-python
This is a small UDP communication using Pyhton. This is version 1 created on 2017-4-17. This code is learned from a youtube program. Here is the link: https://www.youtube.com/watch?v=PkfwX6RjRaI. Later there will be some features added on. 
There are two codes using Python 2.7. If you wanna play with the code. Here is the instruction.

# Step 1: Git clone the files to your local
git clone wth SSH: git clone git@github.com:Linovation/Local-chat-usying-python.git 

# Step 2: Check your python version
In the terminal, type : python --version, if it shows 2.7.X, then you can go to step 3. If it shows 3.X.X, then please convert the code to the style of python 3.

# Step 3: Start the Communication using UDP packet
Start up the server first: python server.py
Start up the client: python client.py
Start up the client side again in a new terminal: python client.py
Hereby, you created a local UDP server, 2 UDP client. (PS: f someone interested why we need a server in between, you can go for the book called : Architecture for Distributed systems. In there it introduces an architecture style called  CLient- Server Style.) 

As you started the client side, you firstly need to type in your Name for chatting. For example, "Name: Linglin" . Then the terminal looks like "Linglin->" means you can start chatting using name as "Linglin". The same procedure, you can create another User in another lient terminal. As two users are created, you can start chatting. Don't forget to refresh the conversation just press "Enter". 

That's it. Simple UDP socket programing and thanks to "DrapsTV" again for such a good tutorial. 


