# Sublime Preferences

My Sublime settings/preferences.

## Usage

*This process will overwrite your existing settings and installed plugins.*
If you have things you want to save, back them up beforehand!

Navigate to Sublime's user packages directory. This can be found by selecting
"Preferences -> Browse Packages..." from the menu. Make sure Sublime is closed
before continuing. Open a shell there and perform the following steps:

```bash
# Remove existing settings
$ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
$ rm -r User

# Clone new settings
$ git clone https://github.com/joshfriend/sublime-settings.git User
```

When Sublime is restarted again, Package Control will install the packages
listed in its config file. Things may look really odd and behave strangely
while this is going on, but once the plugins are installed and Sublime is
restarted, things should go back to normal.
