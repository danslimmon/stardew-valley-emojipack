# stardew-valley-emojipack

A set of Slack emojis related to Stardew Valley. Enjoy!

![abigail](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-abigail.png)
![alex](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-alex.png)
![caroline](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-caroline.png)
![clint](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-clint.png)
![demetrius](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-demetrius.png)
![dwarf](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-dwarf.png)
![elliott](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-elliott.png)
![emily](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-emily.png)
![evelyn](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-evelyn.png)
![george](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-george.png)
![gus](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-gus.png)
![haley](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-haley.png)
![harvey](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-harvey.png)
![jas](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-jas.png)
![jodi](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-jodi.png)
![kent](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-kent.png)
![krobus](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-krobus.png)
![leah](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-leah.png)
![lewis](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-lewis.png)
![linus](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-linus.png)
![marnie](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-marnie.png)
![maru](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-maru.png)
![pam](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-pam.png)
![penny](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-penny.png)
![pierre](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-pierre.png)
![robin](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-robin.png)
![sam](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-sam.png)
![sandy](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-sandy.png)
![sebastian](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-sebastian.png)
![shane](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-shane.png)
![vincent](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-vincent.png)
![willy](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-willy.png)
![wizard](https://github.com/danslimmon/stardew-valley-emojipack/raw/master/images/sdv-wizard.png)

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

# Acknowledgments

All of these images derive from the excellent [Stardew Valley Wiki](https://stardewvalleywiki.com/Stardew_Valley_Wiki), and ultimately from the delightful game [Stardew Valley](https://stardewvalley.net/) made by [ConcernedApe](https://twitter.com/ConcernedApe) and published by [Chucklefish](https://blog.chucklefish.org/).
