# midi-mixer-apc
<b>MIDI Mixer Profile with Peak Meters for the Akai APCmini MIDI Controller</b>

<b>Required Apps</b><br>
MIDI Mixer: https://www.midi-mixer.com<br>
loopMIDI: http://www.tobias-erichsen.de/software/loopmidi.html<br>
Cantabile Lite: https://www.cantabilesoftware.com/free-vst-host<br>
Bome MIDI Translator Classic: https://www.bome.com/products/mtclassic<br>


<b>loopMIDI</b><br>
Create 4 Ports named "Virtual-1" to "Virtual-4"<br>

![01](https://user-images.githubusercontent.com/48880341/115947272-e5c05880-a4c6-11eb-8424-c3a38f32d444.png)<br>


<b>Cantabile</b><br>
Go to Tools --> Options<br>
Set Audio Engine to "Null Audio"<br>
Delete all Audio Ports<br>
Delete all MIDI Ports<br>
Add a MIDI Input Port "Virtual 2"<br>
Add a MIDI Input Port "Virtual 4"<br>
Add a MIDI Output Port "Virtual 1"<br>
Add a MIDI Output Port "Virtual 3"<br>
Add a MIDI Input Port "APC"<br>
Add a MIDI Output Port "APC"<br>

![07](https://user-images.githubusercontent.com/48880341/115947580-ebb73900-a4c8-11eb-980d-d43fd16e2913.png)<br>

Download https://github.com/ovinas/midi-mixer-apc/blob/main/midi-mixer-apc-level.cantabileSong<br>
Load the file in Cantabile (File --> Open Song...)<br>

Routing now should be like this:<br>

![10a](https://user-images.githubusercontent.com/48880341/115951718-925c0380-a4e2-11eb-8f3a-ed3fc8a07ff9.png)<br>


<b>Bome MIDI Translator</b><br>
Set Midi In to "Virtual-3"<br>
Set Midi Out to "Virtual-4"<br>
Activate "MIDI Thru" at Options.<br>
Download https://github.com/ovinas/midi-mixer-apc/blob/main/midi-mixer-apc-level.bmtp<br>
Load the file in Bome MIDI Translator (File --> Open)<br>

![19](https://user-images.githubusercontent.com/48880341/115948214-1b684000-a4cd-11eb-831a-70f1cf47fee0.png)<br>

<b>MIDI Mixer</b><br>
Import the Profile by opening midi-mixer://share/7e3e33ceeaafcee6868533d36950d5e8 in a Webbrowser.<br>
Set Input to "Virtual-1" and Output to "Virtual-2"<br>

![20](https://user-images.githubusercontent.com/48880341/115948894-33da5980-a4d1-11eb-8f69-0bd409f872b6.png)<br>

Assign your Apps/Inputs/Outputs to the Control Groups.<br>

![21](https://user-images.githubusercontent.com/48880341/115949006-0641e000-a4d2-11eb-8f56-a327e795de54.png)
