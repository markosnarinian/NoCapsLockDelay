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

Feel free to open `NoCapsLockDelay.app` with the Automator application on MacOS to inspect the contents.

# Attention

This application must be added to Login Items.
