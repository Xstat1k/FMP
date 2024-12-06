Movement
editied player speed and camera rotation for "fast look/feel"
increased jump height and added an extra jump

basic projectile system 

restarted project to a more simple one so i can get it as poslished as posible

basic card genborator using text edit blueprints to create the cards using a single card actor

made a table

use an invisable actor for card spawn position and + distance after each spawn

genorated as many cards as posible to see how it could handle too many spawning, at 4k ue5 runs at 8 frames and 1 if the camera moves

cleaned up blueprints

User 1 test: "cards are a weird size and hard to see but feel random"

adjusted placement based on user 1 feedback, tilted the cards for a better view and took away the characters movement

added card limit and scoreboard using and or bools to tell if player has balckjack or a 5 card win

updateable int to give player value calc (sum of cards)

reset function that deleted all actors and returns values back to 0

user 2 test: "do i play on my own? it feels good but you start with 2 cards not 1"

added a deal mechanic that checks current player card count if 0 add 2 cards, also added a hard limit to prevent more than 5 cards being used

stick function that saves the users cards and beings the house dealing

included the house in the dealing at first

use a sequence so cards are delt player house player house

gave hosue an actor for dealing as cards where spawining randomly in the world

house also has 2 cards to begin

copied player calc for the house to have one too

included a scoreboard for the house 

user 3 test: "ive never played blackjack but thats cool, so i have to get a better number? how do i know when i win"

added a mess of bools and text editors for the scoreboards and a clacluaator to see when the player and house is stuck and to announce a winner

when i change to cpp switch case and if else would work much better as this bp system is overly complex

swapped inputs form keybinds to a basic widget button system

widget system only allows player to look around when LMB held, i have no idea why this happens and any attempts with the player control it havent worked

moved player cam to compensate

user 1 & 2 test 2: " it works now, sometimes the text bugs out weirdly"
user 2 played for 15 minutes despite being told that i only needed a quick basic test so i will take that as it is enjoyable

attempted to fix the buggy text cannot find out why it does that at all. 

remade the scorboard calc, it works about the same but with fewer nodes

realised in class i havent pushed my dev log once and kept it open on a laptop for a month (dont do that)

added a floating eyeball as the project didnt have a manny model i could use and the table felt empty 

finished project protoype 

already startinbg notes for the logic of how the game works to convert it to cpp, other functions to add (split and chip gamble mechanic) i will be converting the random genorator into a 52 array of cards as randomly genorating a number and suit just feels off? also allows for some form of card counting and better "feel"

double checking it worked for the hand in i discovered a bug where sometimes the player isnt delt to and only the house is, unsure why but there is not enough time to do it for the final version. will explore in own time
