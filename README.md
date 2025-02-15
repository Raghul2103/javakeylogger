# Keylogger
A keylogger is a tool that records keystrokes typed on a keyboard. It can be used for security purposes, such as monitoring computer activity in workplaces or by parents for their children’s safety

# Java-Keylogger
A simple key logger application implemented in Java. It uses [Native Hook](https://github.com/kwhat/jnativehook) library to add global listener for key presses.

## How to Build and Run Project
Build project: 
```bash
mvn package
```
Run ./target/keylogger-jar-with-dependencies.jar file using command:
```bash
java -jar ./target/keylogger-jar-with-dependencies.jar
```
The keys will be written in **keys.txt** file and application logs will reside inside **all.log** file.

## P.S.
Make sure to turn off the keylogger application once you’ve finished logging.
to exit the keylogging use ctrl +c key

## EXAMPLE:
'A' = A

'L' = L

'L' = L


    =[space]

    
'T' = T

'H' = H

'E' = E


    =[space]

    
'B' = B

'E' = E

'S' = S 

'T' = T




