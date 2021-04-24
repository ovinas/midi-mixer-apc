# midi-mixer-apc
<b>MIDI Mixer Profile with Peak Meters for the Akai APCmini MIDI Controller</b>

<b>Required Downlads</b><br>
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
