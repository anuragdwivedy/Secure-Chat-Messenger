
# Secure-Chat-Messenger

Secure Instant Messaging System
author: Anurag Dwivedy

# Installation Steps:

Make sure the following files are available in our working folder:
Key files for server:
	Server Public Key
	Server Private Key
	ChatConf.conf

Key files for client:
	Server Public Key
	ChatConf.conf

Make sure pyDH is installed on both the machines:

To install pyDH, simply:
$ pip install pyDH

For details please refer:https://github.com/amiralis/pyDH 


 # User Credentials: (username/password)

bob/bob
alice/alice
jhon/jhon

# Usage: Server
	python chatServer.py (Initializes the server on port and ip mentioned in the config)


# Usage: Client

	python chatClient.py (Initializes the client and connect to server port and ip mentioned in the config)
	list: gives the list of active users
	send <username> <message>: sends message to the username specified
	logout: logouts the client



# Usage: createPasswd
To register a new user run createPasswd.py present in server folder

	python createPasswd <newusername> <password>

