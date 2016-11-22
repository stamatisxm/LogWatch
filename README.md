# LogWatch
A Tcl/Tk tool for watching dmesg output

<img alt="LogWatch Logo" src="http://ideaware.xyz/images/LogWatch.png" width="48px" height="48px" />


## Interface

Runnning the program spawns:
- 1 control window (1st screenshot)
- 1 display window (2nd screenshot)

The `Refresh Delay` spin button controls the frequency with which the `dmesg` command is run.

The `Pause` toggle button pauses the execution of the `dmesg` command and allows for perusing the output of dmesg.

The status bar in the Display window displays some information *(Refresh Interval, how many times `dmesg` has run and the time of the last run)*

Clicking upon the *Refresh Delay* label brings the LogWatch Display in the foreground.

Clicking upon the Display window status bar brings the Control window in the foreground.

To close the application click on the Display window close button (top right).

### Screenshots

#### Control Window

![LogWatch Control](http://ideaware.xyz/images/LogWatch/LogWatch-SSA01.png "LogWatch Control")

#### Display Window

![LogWatch Display](http://ideaware.xyz/images/LogWatch/LogWatch-SSA02.png "LogWatch Display")