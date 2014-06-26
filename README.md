TtsEngineExample
================

This is an example TTS Engine that breaks Settings app (Settings -> Language & input -> Text-to-speech output).

Please note that installing this engine and setting default language to 'uzbek' will break
Text-to-speech output settings permanently on devices with Android version <= 4.4.3 (aka KitKat)
that can be fixed only by factory resetting the device (unless rooted).

On Android 4.4.4, however, you can simply uninstall the engine to get back to Text-to-speech output settings.

The original source is copied from {ANDROID-SDK}/samples/android-19/legacy/TtsEngine
