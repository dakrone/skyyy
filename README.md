# Skyyy - deal with Skype over dbus

Allows you to do stuff like:

```
% skyyy mute

% skyyy hangup
```

Or, run with just `skyyy` to have a dmenu prompt for which action to
take (or who to call).

## Pre-reqs

```
% sudo apt-get install libdbus-ruby suckless-tools zenity
% gem install ruby-dbus
```

## Known issues

- the chat command is kind of wonky, it's mostly for jumping to unread chats

## TODO

- mute toggle command
