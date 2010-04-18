# gotosleep
gotosleep is a command-line tool for invoking sleep after n seconds on Mac OS X 10.6.

This tool was written because I would often watch The Cosmos (props Carl Sagan) on YouTube with a continuous playlist while trying to fall asleep. If I fell asleep while watching it, the video stays full screen and would drain my laptop battery until depleted. So to conserve energy and the cycle count of my battery, I would rather just set a sleep timer. So instead of paying for one of the few GUI apps out there I wrote this script.

## Installation
Use as-is in checkout directory or copy to a directory in your $PATH such as /usr/local/bin.

    cp -a ./gotosleep /usr/local/bin/gotosleep

## Usage
Call from the command line. The only argument is the number of seconds until you want the computer to automatically sleep.

### Common Usage
    gotosleep 1800 #Invoke sleep in 30 minutes
    gotosleep 3600 #Invoke sleep in 60 minutes
