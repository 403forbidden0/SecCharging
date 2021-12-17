# SecCharging
An application to defend against EM-Surfing side-channel attack

SecCharging is able to protect at least the following four classes of privacy: passcode, keystroke, app, speech.<br>
Passcode:<br> 
SecCharging continues to detect if the user attempts to unlock the phone. If so, it generates simple processes to pollute the voltage signal until the phone is found unlocked.<br>
Keystroke and App:<br> 
SecCharging keeps on monitoring if a tapping happens. If the user taps the touchscreen, SecCharging would randomly generate n processes to change the load deliberately.<br>
Speech:<br> 
Playing the voice will trigger SecCharging to generate random processes continuously until the user stops playing, greatly disrupting the voltage dynamics caused by the voice playing.

Dropzone access for this app should be allowed.
