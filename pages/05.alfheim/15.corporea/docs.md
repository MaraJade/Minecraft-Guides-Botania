---
title: Corporea
taxonomy:
    category:
        - docs
twittercardoptions: summary
articleenabled: false
musiceventenabled: false
orgaenabled: false
orga:
    ratingValue: 2.5
orgaratingenabled: false
eventenabled: false
personenabled: false
restaurantenabled: false
restaurant:
    acceptsReservations: 'yes'
    priceRange: $
---

The Corporea system within Botania allows you to request items whenever you need them. There are a few blocks involved with Corporea and each have different functions within a Corporea network.

### Basics and Concept of Corporea
The basic idea behind Corporea is that its a set of inventories that are connected to each other wirelessly, you will be able to request items from any inventory within your Corporea network. Inventories are not limited to chests but these also include:

* Chests
* Trapped Chests
* Hoppers
* Dispensers
* Furnaces
* And more

Corporea will take items from the top of an inventory. There are 2 main components of a Corporea network, Normal Corporea Sparks and Master Corporea sparks. These work just like regular sparks but they will not transport mana. 

The Corporea sparks can be placed above any chest and can see what is within each inventory they are above, you must palace one of these above each chest you wish your Corporea network to see. 

The Master Corporea Spark will designate other sparks and tell them that they are one whole system, this also needs to be placed above a chest. You can use the Wand of the Forest to check what sparks are connected by right-clicking on the Master Corporea spark. Anything within the inventory underneath the Master Corporea spark can not be found within the system

There is no limit on how far these sparks reach, as long as the chunk they are in is loaded and as long as each Spark is a maximum 8 blocks away from another Spark. This means you can change sparks together running in any direction

You can also dye Corporea Sparks with Floral Powder, once right-clicked with the powder they will not be connected to any network, this enables you to have networks working in parallel with each other. Sparks can also be removed by Shift Right-Clicking with the Wand of the Forest.

### Basic Networks
The Corporea Crystal Cube can show you how many of any item is within your system, once placed down you will need to put a Corporea Spark above them (within 8 blocks of any other Corporea sparks) next you can right-click any material that you already have within your network. This will display the number of that item you have within your network. Remember you need to have the item (such as Iron) within your Corporea network otherwise it will show as 0. Left-clicking the Corporea Crystal Cube will give you 1 of that item, Shift Left-Clicking will give you 1 stack.

Attaching a Comparator to the Corporea Crystal Cube will allow it to emit a Logarithmic redstone output when it detects items within the network.

Items/Signal

0/0 - 1/1 - 2/2 - 4/3 Etc

One of the Common and more important ways to request items via Corporea is via the Corporea funnel. This Funnel will allow you to request a certain amount of a particular item with a Redstone signal. You can connect the Funnel to your system by placing a Corporea Spark above it, next it will require an Item Frame with the specific item you wish to request within it. Giving the Funnel a redstone signal now would give you 1 of that item, to change the amount of items you can right click the Item within the Item frame to turn it, each slight turn represents a different amount of items: 1, 16, 32 and 64. If there are no inventors below the Corporea  Funnel it will place items on top of itself, thankfully it will still place items into inventories up to 2 blocks below the Funnel.

The Corporea Index (once connected to your network) will allow you to see what's in your network and request items from your network via chat commands, You must be standing within 3 blocks of the Corporea Index  for it to work. You will need to be standing next to the index to use chat, these chat messages will appear to others. You can use the following commands:

The rules to determine the requested item name are as follows:

Item name: 1 of the item with the requested name, eg. "iron ingot" requests an Iron Ingot.
Simple plural form of the item name (with -s, -es, -ies): 1 of the item, eg. "peonys", "peonyes" or "peonies" requests one Peony.
"this": requests the item held in the player's main hand.
Appending or prepending ..., ~, ? or +: any item containing the requested string, eg. "?ingot" or "ingot..." will match any ingots.
Rules to determine the requested amount:

"amount (of) item": the requested amount of the item, eg. "10 apples" or "10 of apple" will request 10 Apples.
"(a) stack (of) item": 64 of the item.
"amount stack(s) (of) item": multiple stacks of the item.
"(a) stack and number (of) item", "amount stack(s) (of) item"
"half/quarter (of) (a) stack (of) item": 32/16 of the item.
"all/every (of) item": requests as much as possible.
"count/show/display/tell item": 0 (only displays the stored amount).
"(a) dozen (of) item", "amount dozen(s) (of) item": multiples of 12.
"(the) answer to life(,) the universe and everything (of) name": 42 of the item.


Items can be added to Corporea networks but you will need to set up a subnetwork, this can be done by dyeing Corporea Sparks. Each new system will need a new Master Corporea Spark with its own inventory. This new network could use Funnels which are activated by redstone to pull from one “dump” chest and drop these items into your main request network.

The Corporea Interceptor will send out a Redstone pulse if you request an item that is not within your Corporea network. This does not need to be placed on an inventory but will need a Corporea Spark and an item frame with any item that is not within your network. On its own, this block is not very handy until you come into auto crafting. These can be placed above Funnels which have Crafty Crates below them.

The Corporea Receptor can be placed next to a Corporea Interceptor, when a request is made for an item that cannot be fulfilled the Receptor sends out and keeps a Redstone Signal. It will remember what was requested and will not forget it until the request has been successful.

