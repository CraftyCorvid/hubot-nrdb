# Hubot: hubot-nrdb

A hubot script for retrieving netrunner card information

## Installation

Add **hubot-nrdb** to your `package.json` file:

```json
"dependencies": {
  "hubot": ">= 2.5.1",
  "hubot-scripts": ">= 2.4.2",
  "hubot-nrdb": ">= 0.0.0"
}
```

Add **hubot-nrdb** to your `external-scripts.json`:

```json
["hubot-nrdb"]
```

Run `npm install hubot-nrdb`

Add **hubot-nrdb** to your `external-scripts.json`:

```json
["hubot-nrdb"]
```

## Sample Interaction

```
user1>> hubot nrdb stimhack
hubot>>
Title*​: Stimhack
​*Faction*​: :anarch:
​*Type*​: Event  - Run
​*Cost*​: 0
​*Influence*​: 1
​*Set*​: Core Set
​*Text*​: Make a run, and gain 9:credits:, which you may use only during this run. After the run is completed, suffer 1 brain damage (cannot be prevented) and return to the bank any of the 9:credits: not spent.
​*NRDBURL*​: http://netrunnerdb.com/en/card/01004

http://netrunnerdb.com/bundles/netrunnerdbcards/images/cards/en/01004.png
```
