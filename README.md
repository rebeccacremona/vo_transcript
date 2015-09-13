Get a screenreader transcript of your page
===========================================

Curious how your screenreaders are rendering your pages? Want to see exactly what effect your a11y tweaks are having?

Run this AppleScript to have VoiceOver navigate through your whole page, element by element, recording a transcript to a text file as it goes.

Make some changes to the site, run again, and do a diff, to see what’s changed!

Setup
-----
- Ensure that VoiceOver is configured to be controlled by AppleScript: System Preferences > Accessibility > VoiceOver > Open VoiceOver Utility [button] > General. Check the checkbox, “Allow VoiceOver to be controlled with AppleScript.”

- Ensure that VoiceOver is configured NOT to automatically start reading webpages on page load: System Preferences > Accessibility > VoiceOver > Open VoiceOver Utility [button] > Web > Page Loading. Uncheck both checkboxes next to “When loading a new webpage”. Next to “While a webpage loads” select “Do Nothing.”

- Ensure that cursor wrapping is disabled: System Preferences > Accessibility > VoiceOver > Open VoiceOver Utility [button] > Navigation. Uncheck “Allow cursor wrapping.”

Running
------
Turn off anything that you are concerned might interrupt the script, and take keyboard focus away from the website (instant messenger, calendar reminders...). Open the AppleScript, and set “page” to the desired URL. Set “transcript” to the desired filename for the output. Optionally, mute your speakers. Run the script... and leave your computer completely alone until it’s done running.

NB 
---
This script is configured to start VoiceOver before running, and turn it off when it’s finished. If that isn’t what you want, be sure to tweak!

If there’s an error in the script, for some reason, VoiceOver probably won’t shut off. Turn it off manually by pressing command + F5.

