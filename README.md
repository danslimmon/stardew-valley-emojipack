# stardew-valley-emojipack

A set of Slack emojis related to Stardew Valley

# How To Upload

You'll need a terminal.

1. [Install NPM](https://www.npmjs.com/get-npm)
2. Install `emojipacks`:
```
    mkdir /tmp/sdv-emojipack
    cd /tmp/sdv-emojipack
    npm install emojipacks
```
3. Upload the emojis to Slack (replace things in all caps with the appropriate values):
```
    ./node_modules/emojipacks/bin/emojipacks --subdomain YOUR_SLACK_SUBDOMAIN \
        --email YOUR_EMAIL_ADDRESS --password YOUR_PASSWORD \
        --pack https://s3-us-west-2.amazonaws.com/danslimmon-emojipacks/stardew_valley/stardew_valley.yaml
```
