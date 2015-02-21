# Hubot GitHub Event Announcer

Announces GitHub webhook events. Gotta catch 'em all!

Currently supports:

1. Push events
1. Ping events
1. Issues events

All other events it announces by giving you the JSON supplied by the webhook.

## Installation

Add the package `hubot-github-event-announcer` as a dependency in your Hubot `package.json` file.

```json
"dependencies": {
  "hubot-github-event-announcer": "0.3.0"
}
```

Run the following command to make sure the module is installed.

```bash
$ npm install hubot-github-event-announcer
```

To enable the script, add the `hubot-github-event-announcer` entry to the `external-scripts.json` file (you may need to create this file).

```json
["hubot-github-event-announcer"]
```

## Configuration

The GitHub Event Announcer responds to the URL `http://hubot.example.com/github/events?room=someRoom` where:

1. `hubot.example.com` is the fully-qualified domain name of your instance of Hubot
1. `someRoom` is the name of the chat room where you want announcements to show up

## Copyright

Copyright &copy; 2015 by [Lee Dohm](http://www.lee-dohm.com) and [Lifted Studios](http://www.liftedstudios.com). See [LICENSE][license] for details.

[license]: https://github.com/lifted-studios/hubot-github-event-announcer/blob/master/LICENSE.md
