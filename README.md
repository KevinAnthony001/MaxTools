# MaxTools
 Useful tools to use in Max
 
 
# Tools

### EZRecorder

**Descripiton**: An easy 2-channel recorder that automatically prompts for a save location. Includes *TimeDisplay*. 

Inlet | Function
------------ | -------------
1 | (Signal) Channel 1.
2 | (Signal) Channel 2.
3 | (Int) One/Non-zero "1..." triggers save dialogue, then begins recording to the deisgnated file. Zero "0" stops the recording.

Outlet | Function
------------ | -------------
1 | Outputs recording length in ms. 

&nbsp;
### TimeDisplay

**Descripiton**: Converts milliseconds (int/float) to hh:mm:ss (symbol) for display.

Inlet | Function
------------ | -------------
1 | (Int/Float) Time in milliseconds.

Outlet | Function
------------ | -------------
1 | (Symbol) Time as symbol in hh:mm:ss format.
