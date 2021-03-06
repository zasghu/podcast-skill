## Podcast Player
Listen to episodes of your favourite podcasts

## Description 
Select your favourite podcasts in the home.mycroft.ai settings and listen to episodes from those podcasts.
You can also check with Mycroft if there are any new episodes available from your chosen podcasts.

## Examples 
* "play the latest episode of the startup podcast"
* "play the gimlet podcast reply all"
* "play an episode of the linux unplugged podcast"
* "check for any new episodes"
* "are there any new podcasts available?"

## Credits 
James Poole

## Setup
You can enter your chosen podcasts into the Skills Settings section of the home.mycroft.ai site.
Here you have space to store 3 podcasts. For each one you need to enter a trigger word and the feed
url for the podcast. 
 - The trigger word can be a word of your choice that will usually be just the name 
of the podcast (If the podcast has an unusual name like "The Nerdist" that Mycroft nay have difficulties understanding,
you can change the trigger word to something clearer like "Nerd").
 - The feed url is a url that can usually be found on the podcasts website under the RSS logo.

## Current state
Working features:
 - Listen to the latest episode of your chosen podcast
 - Use the settings in the home.mycroft.ai site to choose 3 podcasts
 - Check for newly available episodes from your chosen podcasts

Known issues:
 - Only tested on a Mark 1 and Desktop installs
 - I have tested this skill with many feed urls. Most of the urls work but some cause issue. I am working to be compatible with those urls that do not work.
 - Not sure how this skill co-operates with other podcast skills

TODO:
 - Select an older podcast, not just the most recent one
 - Add compatibility for a wider range of podcasts, some feeds dont work with the current implementation
