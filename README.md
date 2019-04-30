# TheSonicExperience





Sound Setup:
--------------------------------------------
Step One:

Download SuperCollider at the following link. 

https://supercollider.github.io/download

Now you will be able to open up the following file. 

OSCRecieve.sc

Once opened, follow the instructions to set up the synth def. 

Step Two:

In the top hand corner select

File > Midi Config

Once in this window select your midi device form the drop down menu
and enter in your IP Address. Once completed click and save and then exit the window. 
You should notice now in the bottom bar your midi device and IP Address. 

Step Three:

Click on the CONFIG button to step up your OSC Client. 

At this point you should already have a scale selected. 

Next select either 12 TET or New Scale (This will change which scale is being sonified)

You should notice now that the 8 roman numeral buttons are no longer greyed out. Assuming 
that your SuperCollider server has been instantiated you can now select the 8 roman numeral 
buttons to begin hearing the chords 1 - 8 of your scale. You can change between 12TET or 
New Scale at anytime to compare the difference. 
(Note: Changing from 12TET to New Scale wont take effect until you select a new chord or the same chord again)

Start Midi
--------------------------------------------

The START MIDI button works after the steps listed above have already been completed. 
Once selected you can now start to play your midi keyboard in the scale that you have
designated (Note: This will be monophonic). Regardless of the scale, the 8 frequencies 
displayed in your list will map to all the white keys from C3 to C5. 
Starting at C3 will be the frequency that you entered above to generate your scale from.
The black keys have a different function on the keyboard than usual. From D#3 to G#4 you can use 
the black keys to change between the different chords of the scale. (Note: The black keys in this range
performs the same function as the white buttons in the main program. We've just made them accessible
during real time midi playback). To silence the chords simply press A#4.  

You will note that after you engage START MIDI, the program will be unresponsive. To end midi playback 
and return to the main program you must hit C#3 on your midi keyboard. To resume midi playback simply press the 
START MIDI button again. Repeat this process to change between scales.  

