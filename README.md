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

# Can I trust this?
You can unzip this and open the file with the Automator application on MacOS to inspect the contents.

# Attention
To work, this application needs to be added to Login Items.
