# IRC-Client
* Name: Brandon Briseno & Alfonso Castanos
* SID: 1932124 & 2283681
* Class: CPSC 353-02 (Dr. Fahy)
* Protocol: https://tools.ietf.org/html/rfc2812#section-3.1.5

# Program Description
This is an Internet Relay Chat client program which should follow the following protocol:
*  1)Get info from user
*  2)Receives 5 single line inputs
*  3)Attempt connection to IRC Server
*  4)Establish socket connection
*  5)Send server data
*  5)Wait for PING msg from server to the client
*  6)PONG msg back to the server from the client
*  7)Create/join chatroom
*  8)Self promotion
*  9)Listen for commands
*  10)/quit on command or kick

## Instructions:
1) Compile: ```javac -classpath pircbot.jar;. *.java```
2) Run: ```java -classpath pircbot.jar;. BotMain```
3) Test: https://client00.chat.mibbit.com/?channel=%23TeamSameTeam&server=irc.synirc.net


## Checkstyles:
```java -jar checkstyle-8.8-all.jar -c google_checks.xml *.java```
