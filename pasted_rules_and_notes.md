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
- no racism, sexism, transphobia, bigotry, etc. one warning before a ban.
- avoid spamming or off-topic memes outside of #off-topic. i don't *entirely* care about people staying on topic, but especially random memes should be in #off-topic.
- no badmouthing related communities or bringing in outside issues
- dont self-promote or promote other discords without permission
- avoid politics and heavy personal subjects. 
- no NSFW stuff (no AD games either, except ultrakill (though if more edge cases like that exist you can ask))

## game rules

- hint games are actually allowed since they have less of an impact on the game
- cheesetracker will be mandatory. since this a non-standard async, instead of using cheesetracker in the normal way, i'll keep the cheesetracker from the *first* run, and then every time you play, you need to mark BK in that cheesetracker (even if you aren't actually BK, and even though it's on a different run)
  - activity is expected every 3 days, so mark BK on the aforementioned first cheesetracker. i'll ping you if you're over 3 days whenever i check in. if i ping you more than twice, we'll have to figure out what we're gonna do with your slot if you can't actively play it.
- if you're playing a manual, it is your responsibility to make sure you're actually adhering to logic, and actually sending and recieving deathlinks yourself.
  - if you get somewhere in-game that is actually out of logic, you can send that check. but, if you're just sending random checks out of logic, one warning before a ban.
- if you're tired of your game, don't just go around cheating because you're tired. instead, ask me, and we can work something out. this async can be changed in the middle!
- release auto, collect auto

## what's this async's deal?

most roguelikes nowadays have a few key features:
- if you die, you start over from the beginning.
- each run is randomly generated.
- there are upgrades that persist between each run, and you grow stronger after each one.

this async has all of those properties!
- death link is on, we have an amount of lives, and when a death_link is sent, we lose one life. once we're out of lives, the run (the whole async) will end and we'll have to start over.
- (it's a randomizer so it's normally generated randomly)
- some items will persist between runs, and the async will grow easier each time, as more things are unlocked.

yaml submission deadline: <t:1731085200:F> <t:1731085200:R>
earliest start date: <t:1731344400:F> <t:1731344400:R>

## yaml submission rules

- do them in #yaml-submissions
- you may submit `1 world`. however, since this async keeps regenerating, your yaml is allowed to pick from up to `6 games` randomly.
- if you don't have as much free time, consider playing games that can BK more quickly.
- supported and unsupported are fine, and if you're playing manuals, you must use weighted game options to make them appear only 1/3 of the time (or less).
  - so for example, if you're playing Hollow Knight and Manual_DeckedOut2_mp3 both with weight of 1, that's not allowed because the manual appears 1/2 of the time.
  - if you're unsure what i mean, check my example submission. also, please ask about manuals before submitting them.
- if unsupported or manual, please link to the apworld github or the discord thread (or just put it there if not applicable)
- `death_link` must be enabled. if your game sends deathlink but doesnt receive it, that's fine, but if it receives but doesn't send then that's not fine.
  - settings that make certain things not send deathlinks or deathlink amnesty are fully allowed.
- no extremely lengthy games (OSRS or Allsanity/Perfection SDV) or games that require hundreds of items to beat.
- avoid having massive amounts of the same progression item in your game. (stuff like low DLCQ coin bundles). 
  - also, avoid massive amounts of filler too. this is less of an issue, though.
- don't go too crazy with start inventory and start hints! and don't start_inventory progression items.
- i highly recommend you play with difficult settings! you may be unsure if you can even beat a game at first, and that's fine. i'll be **changing yaml options** as a permanent upgrade.
  - if you wish to opt into that, inside your yaml, add comments (with #) next to yaml options. check my example submission to see what i mean!
  - please don't mark settings that change how many progression items are required, unless you're doing a macguffin hunt goal. it's the equivalent of me just locking away progression items, which i'm trying to avoid in the first place. things like reducing strawberries to goal in C64 is good, but things like disabling move rando is not.
- i also recommend you play with a lot of random settings, as it'll help cause more variety. if you're trying to do both hard and random settings, things like weighted options or `random-high` can help.
- please compress your yaml down as much as possible. i'll be editing yamls *frequently* this async, so i'd like to not have massive walls of text explaining every yaml option everytime i want to edit something.
- with your submission, list a few useful/filler items in your game. you *can* submit progression items, but please don't submit too important ones.
  - only add them if they *increase your survivability* or *make goaling easier*.
  - you must also list whether these items are *unique* or *duplicate*. what i mean is: is there exactly one copy of this item? or are there several in the pool?
  - don't list every copy of a duplicate item.
- *collectively, you must submit 10-20 yaml changes and useful items.* if your game has fewer useful items, but a lot of yaml settings that can make things difficult (that i'd change to make things easier), that's what this is for, and vice versa.
- also, please list some filler items for your game. ideally, 2-4 filler items that there are several copies of in the pool.
  - if your game is like Terraria, and has a lot of filler items that there are only 1 of, please mention that!
- mention your **origin**! witches often like to remain in the shadows, and their origins reflect that. with your submission you must list your origin as one of these eight:
  - tundra
  - hell
  - cavern
  - shadow realm
  - marsh
  - moon
  - mountain
  - under the ocean
- i would like to have a balanced count of origins, though. if you have no preference (or have a secondary preference), please list it.
  - these origins *do* matter, but perhaps not as much as you might expect.

# welcome to Wayward Witches: roguelike async 2

we are a coven of witches, on a journey. the world we find ourselves in is not safe for us, but each time we perish, we end up right back at the beginning of our journey. thankfully, our nature as witches allows us to cast spells to keep persisting through it all. it's a matter of time before we reach our goal, but how much Time will it take? 

*looks like somebody played hades 2!*

that's the extent of the lore to this async, but it informs the design and the general theming of things.
yaml submission deadline: <t:1731085200:F> <t:1731085200:R>
earliest start date: <t:1731344400:F> <t:1731344400:R>

the entirety of the async will be within this discord server: https://discord.gg/tGHg2Q4aJ9

## forum post of actual announcement

i said it'd take a while, but the second roguelike async is open for yaml submissions! all of it will be on a different discord server, including yaml submissions.
*with death comes a reset, but we learn and grow stronger over time. inevitably we will win, but it's only a matter of Time...*

## the cauldron

welcome to **the cauldron!** here, there will be a list of all *spells* (permanent upgrades) we can *cast* (spend resources on). most of these upgrades unlock *multiple* things, but they will all have cryptic hints relating to one specific item. we'll be spending the varied items we find inside the multiworld on these upgrades. while this is a skill tree, i'll just be listing every item you can currently purchase, and how many things it directly opens up. nothing in the skill tree requires multiple other entries at once, or can be opened up by one of multiple. also, if you can guess a cryptic hint, it'll be a little cheaper. please keep all cauldron discussion in #item-discussion, so i can see what things people want to get in one place.