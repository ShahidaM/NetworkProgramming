# NetworkProgramming

Solution & Solution 1
Client &amp; Servers assignment

Write a Python script to create a UDP Server and Client using
the Python socket standard library. 
In this scenario, 
1) the client sends a message to the server, and the server replies
with a modified version of the message.
2) The modification task involves doubling every vowel in the
received message before sending it back to the client over the
UDP connection.
Example client execution log:
Enter message to send to server: Hello World!
Received modified message from server: Heelloo Woorld!
Example Server execution log:
Server listening on 127.0.0.1:12345...
Sent modified message back to ('127.0.0.1', 56660): Heelloo Woorld!

Solution2
Write a Python script to demonstrate "Raw
Network Conversation." Use the socket library to request the
ip-api JSON endpoint(https://ip-api.com/docs/api:json) to GET
your IP Geolocation, such as city, regionName, country, lat,
and lon.

Solution3 server & Client
Write a Python script to create a TCP Server and Client using the Python socket standard library to develop a game "Guess the number".
The game will follow as:
1) The server will choose a random number between 1-10
2) The client will have only 5 attempts to guess the correct number
3) The client will only win if he guesses the correct number within 5 attempts.
