# Creating and Using Variables in Shell

A variable is a character string to which we assign a value. The value assigned could be a number, text, filename, device, or any other type of data.

## 1. Create Variable in script and use it
```
#!/bin/bash

NAME="John"
COLOR="RED"

echo Hi $NAME, is $COLOR favorite color?
```

## 2. Creating and using variable on terminal

```
# MYHOSTNAME=$(hostname -f)
# HOSTMEM=256MB

# echo "Host name is $MYHOSTNAME and RAM configured on this node is $HOSTMEM"
```


## 3. Environment Variables
Environment variables are like our own, except they are defined for us, by the system. They allow us to know things about our script's environment.
  PATH
  ENV
  TERM
  EDITOR
  HOME
  HOSTNAME
  USER


## 1. Create a shell script and use some ENV variables
```
if [ -z $EDITOR ]
then
	echo "EDITOR IS EMPTY"
else
	echo "The EDITOR IS $EDITOR"
fi
```


## CHALLENGE:
  Create a script named env.sh
  Display a sentence which includes "username" "computername" & "home directory"



