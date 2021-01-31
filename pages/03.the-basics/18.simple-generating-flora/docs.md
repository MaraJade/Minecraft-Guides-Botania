---
title: 'Simple Generating Flora '
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
media_order: 'Hydrangea.jpg,endoflame.jpg'
---

Simple Generating Flora are cheap and work “ok”, they will help you get started and help you generate a little Mana. Some of these flowers are passive and some require items to generate Mana, most of these can be automated.

Flowers **MUST** be linked to a Mana Spreader, unlinked flowers will not generate Mana, also flowers can not be bound to Mana Pools. There are a few ways to bind flowers to Mana Spreaders. 

If you first place down a Mana Spreader and then a flower, the flower will bind to the nearest Mana Spreader. You can also choose what Mana Spreader you wish to bind a flower using Binding mode and Shift Right-Clicking the flower and the Mana Spreader. Placing a Mana Spreader after placing flowers requires each flower to be linked to the Mana Spreader manually.

If you destroy a Mana Spreader that has been bound to a flower you can see where the Mana spreader was by hovering over it with the Wand of the Forest. You can also check if a flower is bound to a certain Mana Spreader by hovering over it, this will cause the Mana Spreader which is bound to the flower to be highlighted.

Hovering over flowers will also display a Mana Spreader with either an X or a checkmark, this will tell you very quickly if the flower is bound to a Mana Spreader or not.

>>>>> It takes 2 seconds to check if a flower is bound to a Mana Spreader and each flower should be checked!

Basic Flowers only need petals to be crafted fortunately, there are 2 flowers you can start off with.

### Hydroangeas
This Mana generating flower will consume still water that is placed at the same height as the flower in a 3x3 area around it and produce Mana, these flowers also function faster when it rains. These flowers will decay after 1 hour so they will need to be replaced.

This flower will **EAT** any still water around it, so having infinite water sources around this flower is advisable.

![](Hydrangea.jpg)

Remember to link your flowers to a Mana Spreader!

### Endoflame
The Endoflame will produce mana when any burnable materials are dropped within its range, the Endoflame will burn anything that can be burned within a furnace apart from items that produce a by-product such as Lava Buckets (buckets being the by-product). The Endoflame will Consume any burnable material 1 at a time so throwing down lots of Coal will not speed up the process and could lead to coal despawning. 

Each product that is burned will burn for half of the time it takes to burn within a Furnace, Coal lasts for 1,600 ticks within a furnace and 800 ticks within an Endoflame. The Endoflame can only burn the equivalent of four times the value of a block of coal. One block of coal lasts 800 seconds (16000 ticks), which smelts 80 items this value x 4 is around 64,000 ticks, if a burnable item is over this value it will simply be wasted as an Endoflame only lasts up to 64,000 ticks. 

Most mod fuels will work with the Endoflame!

Throwing down coal is not the most efficient way of setting up an Endoflame, Ideally, you will want a system that will generate Mana on its own, the only thing you might need to do is add coal. We know that throwing down a bunch of coal is a bad idea but we can make use of open crates.

Open Crates will drop any items deposited one at a time onto the ground below them at a constant rate. You can feed items into the Open Crate via hoppers or tubes from other mods. You can also control open crates with Redstone.
Set down the following items in order

Mana Pool - Mana Spreader  - Endoflame - Wooden Pressure Plate - Open Crate (on top of the pressure Plate) - Redstone - Dirt - Redstone on the Dirt - Redstone. 

Next, add a Lever onto the Open Crate and a Hopper attached to the Open Crate.

Fill the hopper with Coal (or any fuel of your choosing).

![](endoflame.jpg)

This will cause One coal to drop, the Endoflame to Eat the coal and burn it, another coal will drop but will not despawn, once the Endoflame is done with the first bit of coal it will eat the next one on the ground. This will continue forever until you run out of coal or when the Mana Pool, Mana Spreader and Endoflame are all FULL. 

It's a good idea to move the Mana from the Mana Pool where the Endoflame is located if you are off mining or exploring the world as these can fill rather quickly.

This setup is probably used by most people as their first automated Mana generation set up and as long as you keep an eye on it then it will always generate Mana. You can expand this set up with more Endoflames and Mana Pools.


