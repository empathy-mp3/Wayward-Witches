# rules and notes

## initial forum post

most roguelikes nowadays have a few key features:
- if you die, you start over from the beginning.
- each run is randomly generated.
- there are upgrades that persist between each run, and you grow stronger after each one.

this async has all of those properties!
- death link is on, and each death reduces our lives by 1. once we're out of lives, the run (the whole async) will end and we'll have to start over.
- (it's a randomizer so it's normally generated randomly)
- some items will persist between runs, and the async will grow easier each time, as more things are unlocked.

this is the second in the roguelike series of asyncs. by popular vote, it'll be on a different discord server, and yaml submissions aren't open yet.
i'm mostly gonna be discussing design for the next couple weeks, and then i'll open up yaml submissions and the server at the same time.
this async has both a name and a theme, but honestly i'll keep them as a surprise (for fun!). i think people come here for the name "roguelike async" anyway.
all the people that reacted to [this message](https://discord.com/channels/731205301247803413/1264701243603947550/1279282105162928180) will be pinged once yaml submissions and the discord server are open. if you're not interested in the discussion, and want to be there for the async itself, feel free to wait until then and react to that message.

it is my hope that this async will be significantly less annoying than the previous. while many people enjoyed it the whole time, many others grew tired of playing the same game over and over again. for that reason, i'll only let players have *one* slot that randomly chooses between up to *six* (number may change) different games.
as for issues with manuals that occurred last async, i'm considering making it so that manuals are randomly chosen up to a third of the time (so that Hollow Knight with weight of 2 and a manual game with weight of 1 is allowed, but if they were both 1 weight, then it'd be a manual 1/2 of the time). the problem is, like, i fully trust someone like Alexander230 to be fully reasonable about manuals. if he dies ingame, i trust him to actually go through with sending the deathlink. but i shouldn't be inconsistent in my rules of this sort of thing. as much as i trust certain people to be reasonable about manuals, if i don't do *something* about it, the same incident will happen once more.
i'll also likely have a much more stable sleep schedule this time, and i'll pace myself more. the daily cycling shop made it so that i had to be constantly there to maintain the shop, especially since we'd need to buy a lot of things immediately after they become available. after completely scrapping the cycling daily shop altogether, this'll be less of a concern. all permanent upgrades will still be able to be purchased in the days after they become available.
as discussed last time, releases will not be permanent. i'm planning on making it so that all players have to goal on the same run, but that might drag on for way too long. perhaps it'd be better if everyone has to goal *once*, but releases don't stay between runs. i'm not sure, though. i do still like the first idea, despite how long it might take. i'm open to input on this. what i *do* know is that this async will most assuredly be longer than the last one.

## planning channel post

the second roguelike async has a forum post! it's not open for yaml submissions yet, but i'll be discussing design for the next couple weeks before it opens up (since the design is going to be *way* different, and a lot more complex). it will be on a different discord server once it does open up.

## discord server rules

- be kind to others!
- have fun!
- no racism, sexism, transphobia, bigotry, etc. 
- avoid spamming or off-topic memes outside of #off-topic. i don't *entirely* care about people staying on topic, and it's perfectly fine if players are having a completely unrelated discussion in #general, but especially random memes should be in #off-topic.
- no badmouthing related communities or bringing in outside issues
- dont self-promote or promote other discords outside of #self-promotion channel
- avoid politics and heavy personal subjects. 
- no NSFW stuff (no AD games either, except ultrakill (though if more edge cases like that exist you can ask))

## game rules

- hint games are actually allowed since they have less of an impact on the game
- cheesetracker will be mandatory. since this a non-standard async, instead of using cheesetracker in the normal way, i'll keep the cheesetracker from the *first* run, and then every time you play, you need to mark BK in that cheesetracker (even if you aren't actually BK, and even though it's on a different run)
  - activity is expected every 2.5 days (just because this is gonna be a faster pace async), so mark BK on the aforementioned first cheesetracker. i'll ping you if you're over 2.5 days whenever i check in. if i ping you more than twice, we'll have to figure out what we're gonna do with your slot if you can't actively play it.
- if you're playing a manual, it is your responsibility to make sure you're actually adhering to logic, and actually sending and recieving deathlinks yourself.
  - if you get somewhere in-game that is actually out of logic, you can send that check. but, if you're just sending random checks out of logic, one warning before a ban.
- if you're tired of your game, don't just go around cheating because you're tired. instead, ask me, and we can work something out. this async can be changed in the middle!

## what's this async's deal?

most roguelikes nowadays have a few key features:
- if you die, you start over from the beginning.
- each run is randomly generated.
- there are upgrades that persist between each run, and you grow stronger after each one.

this async has all of those properties!
- death link is on, we have an amount of lives, and when a death_link is sent, we lose one life. once we're out of lives, the run (the whole async) will end and we'll have to start over.
- (it's a randomizer so it's normally generated randomly)
- some items will persist between runs, and the async will grow easier each time, as more things are unlocked.

## yaml submission rules

- do them in #yaml-submissions
- you may submit **1 world**. however, since this async keeps regenerating, your yaml is allowed to pick from up to **6 games** randomly.
- if you don't have as much free time, consider playing games that can BK more quickly.
- supported and unsupported are fine, and if you're playing manuals, you must use weighted game options to make them appear only 1/3 of the time (or less).
  - so for example, if you're playing Hollow Knight and Manual_DeckedOut2_mp3 both with weight of 1, that's not allowed because the manual appears 1/2 of the time.
  - if you're unsure what i mean, check my example submission. also, please ask about manuals before submitting them.
- `death_link` must be enabled. if your game sends deathlink but doesnt receive it, that's fine, but if it receives but doesn't send then that's not fine.
  - settings that make certain things not send deathlinks or deathlink amnesty are fully allowed.
- with your submission, list up to 5-10 useful/filler items in your game. you *can* submit progression items, but please don't submit too important ones.
  - only add them if they *increase your survivability* or *make goaling easier*.
  - specifically, keys that unlock areas are definitely not allowed, and neither are major abilities like `Mothwing_Cloak` in hollow knight.
  - but things like guns in ultrakill (ideally ones that don't unlock *too* many checks) are allowed. just know you aren't finding it until later.
  - if you're playing a roguelike where the only items are progression, then i guess that's fine
  - you must also list whether these items are *unique* or *duplicate*. what i mean is: is there exactly one copy of this item? or are there several in the pool?
  - don't list every copy of a duplicate item.
  - if the items you're listing are *relatively insignificant*, you can list more than 10 of them.
- also, please list some filler items for your game. ideally, 2-4 filler items that there are several copies of in the pool.
- no extremely lengthy games (OSRS or Allsanity/Perfection SDV)
- avoid having massive amounts of the same progression item in your game. (stuff like low DLCQ coin bundles). 
- i highly recommend you play with difficult settings! you may be unsure if you can even beat a game at first, and that's fine. i'll be **changing yaml options** as a permanent upgrade.
  - if you wish to opt into that, inside your yaml, add comments (with #) next to yaml options. check my example submission to see what i mean!
  - please don't mark settings that change how many progression items are required, unless you're doing a macguffin hunt goal. it's the equivalent of me just locking away progression items, which i'm trying to avoid in the first place. things like reducing strawberries to goal in C64 is good, but things like disabling move rando is not.
- i also recommend you play with a lot of random settings, as it'll help cause more variety. if you're trying to do both hard and random settings, things like weighted options or `random-high` can help.
- please mention your 

