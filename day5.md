##  Bash scripting:
###  echo - 
	#! /bin/bash (header file)
	echo "Hello, World" (echo = print)
	save in .sh extension
### to print using a variable 
	NUMBER=5(no space)
	echo "The number is $number"
###  to take input from user
	read: reads input from user
	read -p "Enter name:" NAME
	echo "you name is $NAME"
	syntax: read -p "prompt msg:" [variable]
### Conditions and branching:
	read -p "Enter nuum:" NUM
	if[space][[space]$NUM -gt 5[space]]; then
		echo "Number is greather than 5"
	else
		echo "Number is less than 5"
	fi	
	where:
	-gt :greater than
	-ls :less than
###  Fucntion and calls:
	f_name(){
		echo "Plain_text"
	}(definition)
	greet(call)
	
	greet(){
		name = $1 or
		echo "Hello $1"(receiveing argument)
		}
		greet "aaluu"(passing argument)
###  command line args:
	./new.sh hello hi
	echo "first arg: $0"
	echo "second arg :$1"
	-takes hi and hello from command line 
