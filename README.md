# My AppleScripts

This is a collection of AppleScripts I've written, primarily for use with the VoiceOver screen reader. A lot of these things have more modern/improved alternatives, but I figured I'd put this here in case its useful to someone.

## Scripts.

### Battery Status.

This script speaks your battery level, and its state (e.g. charging, charged, etc).

### Close Windows.

Probably the only script that doesn't depend on VoiceOver to run, just to output, this script closes all windows and/or unsaved documents of any applications that support AppleScript. I had a reason for writing this once upon a snowflake, I just don't remember what it was.

### CPU Usage.

Originally written to help a friend with a project, this script obtains your CPU usage through top and speaks it to VoiceOver.

### Indentation.

This script speaks the number of proceeding tabs/spaces in VoiceOver's last spoken phrase. Useful for programmers, mostly. There are better choices for that now, but I guess it could still be useful for writing nicely-formatted essays or something.

### Last Phrase.

Basically a substitute for VO+Z (repeat last spoken phrase), but this one doesn't play sounds along with it, or pause. I like this better personally, and I still use it actually.

### OS Version.

Another script I initially wrote to help a friend out, this simply reports your OS version through VoiceOver.

### Time and Date.

Probably the only other script out of these that I still use daily, this one speaks the time and date in a nice format. VoiceOver has this ability, but the time doesn't display seconds and the date doesn't give the day of the week, two things I very much care about, so this was born.

### Uptime.

Pretty simple script, it just speaks your computer's uptime through VoiceOver.

## Notes.

If you want to make these output to something that's not VoiceOver, its quite easy. A few of them (namely Indentation and Last Phrase) depend on VoiceOver, but they all check if its running with AppleScript support, and only speak in that case. It wouldn't be too hard to add your own methods of output, I just never needed them and as such never bothered.
