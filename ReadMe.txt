this version of the LookUp Event Table dumps the current state of the Event Table into the text file on a photo event. 
It also reads two ADC128D818 sesnors ("16 sensors") and stores them in the text file whenever a photo is taken.

The size parameters in slot4 (line 428 immediately under the "textfinished" label) must match the length of the table in Slot2. 
