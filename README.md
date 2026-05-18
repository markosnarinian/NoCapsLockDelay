# NoCapsLockDelay
MacOS Automator application that sets CapsLockDelayOverride to 0.

# Installation & Usage
1. Download the ZIP file.
2. Unzip into Applications or iCloud Drive/Automator.
3. Add NoCapsLockDelay.app to Login Items.

# How it works
This application executes the following shell command when launched:
```
hidutil property --set '{"CapsLockDelayOverride":0}'
```

# Attention
To work, this application needs to be added to Login Items.
