#!/bin/sh
if [ "$#" -eq 0 ]
then
    echo "Please insert input argument currectly"
    exit 1
else
    if [ -d "$1" ]
    then
    	echo "$1 Is a Directory"
    else
    	echo "It's not a directory ....."
    	exit 1
   	fi 
fi
