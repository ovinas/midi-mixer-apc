# midi-mixer-apc
<b>MIDI Mixer Profile with Peak Meters for the Akai APCmini MIDI Controller</b>

<b>Required Apps</b><br>
MIDI Mixer: https://www.midi-mixer.com<br>
loopMIDI: http://www.tobias-erichsen.de/software/loopmidi.html<br>
Bome MIDI Translator Classic: https://www.bome.com/products/mtclassic<br>


<b>loopMIDI</b><br>
You just need one Port. I named it "Virtual-1"<br>

![01a](https://user-images.githubusercontent.com/48880341/115956440-f1c70d00-a4fc-11eb-93ac-643d93d0f7fe.png)<br>


<b>Bome MIDI Translator</b><br>
Set Midi In to "Virtual-1"<br>
Set Midi Out to "APC MINI"<br>
Activate "MIDI Thru" at Options<br>
Download https://github.com/ovinas/midi-mixer-apc/blob/main/midi-mixer-apc-level.bmtp<br>
Load the file in Bome MIDI Translator (File --> Open)<br>

![19](https://user-images.githubusercontent.com/48880341/115948214-1b684000-a4cd-11eb-831a-70f1cf47fee0.png)<br>

<b>MIDI Mixer</b><br>
Import the Profile by opening midi-mixer://share/7e3e33ceeaafcee6868533d36950d5e8 in a Webbrowser<br>
If that profile isn't available anymore, download https://github.com/ovinas/midi-mixer-apc/blob/main/APCmini-Peak.json and copy the file to C:\Users\username\AppData\Roaming\midi-mixer-app\profiles (adapt to your PC settings)<br>
Set Input to "APC MINI" and Output to "Virtual-1"<br>

![20a](https://user-images.githubusercontent.com/48880341/115956506-787bea00-a4fd-11eb-837e-20ee1c6569c1.png)<br>

Assign your Apps/Inputs/Outputs to the Control Groups.<br>

![21](https://user-images.githubusercontent.com/48880341/115949006-0641e000-a4d2-11eb-8f56-a327e795de54.png)<br>

All three Apps have a "Start with Windows" Option that you may want to activate.<br>

Watch it in Action here: https://youtu.be/ZVpBBi5jRFk
