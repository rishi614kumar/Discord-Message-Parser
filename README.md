# Discord Message Parser

This Python script cleans and processes Discord messages for use in modeling or for analytical purposes.


The scrape command from [Doppelganger Bot](https://github.com/rishi614kumar/Doppelganger-Discord-Bot) can be used to obtain messages from any accessible user. Follow the steps up through the scrape command if needed.

This script is required for full Doppelganger Bot usage.

# Table of Contents
- [Overview](#Overview)
- [Usage](#Usage)

# Overview

The Discord Message Parser can be used to parse multiple jsons of discord message data at once. It does the following:

1. Concatenate all input jsons.
2. Breaks up Discord's Date field in to year, month, day, hour.
3. Adds an alias for each Discord Username (e.g. fuzzybunny#1281 --> Kevin)
4. Saves a new master json with all the changes
5. Goes through the messages for any set of users to clean and write them to a train.txt file for model training. 

You can choose whether or not to include aliases for each message in train.txt



# Usage
Optional: Follow [Doppelganger Bot](https://github.com/rishi614kumar/Doppelganger-Discord-Bot) instructions to obtain jsons of your desired messages.

Simply download discord_message_parsing.py and fill the settings before running.


The output txt file can be used for GPT-2 model training.






