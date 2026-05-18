# NoCapsLockDelay

MacOS Automator application that removes the caps lock toggle delay

# Installation & Usage

## Manual installation

1. Clone the repository.
2. Add `NoCapsLockDelay.app` to Login Items.

# How it works

This application executes the following shell command when launched:

```
hidutil property --set '{"CapsLockDelayOverride":0}'
```

That's it.

# Can I trust this?

Feel free to unzip `NoCapsLockDelay.app.zip` and open the file with the Automator application on MacOS to inspect the contents.

# Attention

To work, this application needs to be added to Login Items.
