# Overall structure

![Overall structure](architecture.png)

# Manager
Manger responsible for management topics, definitions

#Push
Push to define multiple client access protocols, such as websocket, longpoll, socketio ....; AKka actor used to manage each connection, a connection is a actor;

#Region

Region responsible topic partition, maintaining the connection status, message received, message exchange; http protocol which provides an interface to query each topic restfull inside information.