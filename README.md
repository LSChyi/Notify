# Notify
Simple macOS notification without any dependencies.  
`notify` is extremely helpful when running a time-consuming command. It spares users from staring the terminal, or need to check the result from time to time. Notify will notify user when the command is done, with a simple report that shows whether the command is succeeded or failed.

## Installation
Simply download the notify script and make it as executable (if it is not after downloaded), then copy it into `/usr/local/bin`.  

## Usage
Just add `notify` before the command you want to executed, ex:  
```
notify curl google.com
```  
. After the command is finished, the notifications of macOS will get a notification.