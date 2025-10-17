# Audio Analysis of Charlie Kirk's Death

This project was created to analyse the audio from the videos of Charlie Kirk's death.

## Simulation

A simulation was created in [Blender 4.1](https://www.blender.org/download/) to visualize the scenario
and better understand the audio time offsets for each recording, and the reflections and echoes of the gunshot.

![Blender Screenshot](https://github.com/TheBengineer/Kirk/blob/main/Images/Blender-Screenshot.png)

> **_NOTE:_**  The simulation runs at 1/10th real-time speed to allow for more accurate audio analysis.
> 
> EG: 240 frames = 1 second of real-time audio.


## Results:

Audio from the 5 videos was loaded into [Audacity 3.7.5](https://www.audacityteam.org/download/)
and aligned to Charlie's last words.
![Audacity](https://github.com/TheBengineer/Kirk/blob/main/Images/Audacity.png)
The differences in the offset of the gunshot sound from each recording was measured.

Then the Simulation was used to determine the number of frames between a reference 
sound from Charlie's position and the gunshot sound reaching each microphone position.
![Table](https://github.com/TheBengineer/Kirk/blob/main/Images/Notebook-Table.png)

The Number of frames correctly matched the audio analysis results within ~5% for all sources, confirming the simulation's accuracy.

