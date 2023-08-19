# Steam Deck Battery Tracker

Simple plugin to track battery history for your Steam Deck as well as power stats.

# How to install (it's not on the plugin store)

Make sure you have a [sudo password](https://www.dexerto.com/tech/how-to-set-a-sudo-2031183/) set up. Go to desktop mode, in a terminal run

```
wget https://github.com/safijari/steam-deck-battery-tracker/releases/download/0.1.0/steam-deck-battery-tracker.zip -O /tmp/plugin_.zip && sudo unzip -o /tmp/plugin_.zip -d /home/deck/homebrew/plugins/ && sudo systemctl restart plugin_loader.service
```