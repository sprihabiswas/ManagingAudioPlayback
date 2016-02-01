# ManagingAudioPlayback
- A guide to managing audio streaming and controls in Android (Part of the series Mastering Android)

Covered here are :
# Controlling your App's Volume and Playback.

- Identify which Audio Stream to Use (Android maintains a separate audio stream for playing music, alarms, notifications, the incoming call ringer, system sounds, in-call volume, and DTMF tones. This is done primarily to allow users to control the volume of each stream independently. Most of these streams are restricted to system events.So mostly we'll be be playing our audio using the STREAM_MUSIC stream)
- Use Hardware Volume keys to control your app's Audio Volume
- Use Hardware Playback Control keys to control your app's Audio Playback


# Managing Audio Focus

- Request Audio Focus.
- Handle the loss of Audio Focus.
- Duck!


# Dealing with audio output hardware.

- Check which hardware is being used.
- Handle changed in the audio output hardware.
