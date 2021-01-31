---
title: 'Spark Tinkerer/Augments'
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

Sparks on their own are not very useful but augments can be added to makes any spark much more useful. Spark Augments can be applied by right-clicking them onto sparks and can be removed by using the Wand of the Forest by Shift Right-Clicking. Only one Augment can be applied to a spark at a time.

### Spark Augment: Dispersive
When applied to Spark that is above a Mana Pool any player within a 12 block radius will have their worn mana containing items such as Ring of Mana and carried items refilled. This does not remove the sparks function to move Mana constructs that need Mana.

### Spark Augment: Dominant
When applied with Right-click to a Spark on a Mana Pool, the Spark will try to draw Mana from all Mana Pools with Sparks within 12 blocks to its Mana Pool until it is completely full. It will still allow Sparks applied to natural constructs to pull Mana when needed.

One potential use of this is to create a storage system which utilises multiple Mana Pools. All incoming mana would be directed to a mana pool with a Spark which has the Recessive Augment - this will then distribute mana to all nearby pools with unmodified sparks. Any device wishing to draw mana out of the storage system, such as a Mana Mirror, would do so via a Mana Pool with a Spark which has the Dominant Augment, allowing it to draw from all nearby pools with unmodified sparks.

### Spark Augment: Isolated
When applied with Right-click to a Spark on a Mana Pool, the Spark will no longer interact in any way with other Sparks on Mana Pools. It will still allow Sparks applied to natural constructs to pull Mana when needed. 

### Spark Augment: Recessive
When applied with Right-click to a Spark on a Mana Pool, the Spark will try to send Mana to all Mana Pools with Sparks (1) within 12 blocks from its Mana Pool until it is completely empty. It will still allow Sparks applied to natural constructs to pull Mana when needed. Recessive Sparks are especially useful together with the Spark Augment “Dominant”, by applying Recessive Sparks to your Mana generating pools (for instance fed by a battery of Kerimekus), then having several pools without augments (16 pools, for instance, allows you to almost instantly craft terrasteel) and add “Dominant” sparks to your high mana spenders (like loonium Flower,Orchid, Runic Table, Catalyst), you can effectively build a huge Mana Storage.

### Spark Tinkerer
When placed adjacent to a Mana Pool with a Spark, this block will allow for automated swapping of any Spark Augment.

After placing the Spark Tinkerer, a Spark Augment can be added to it by right-clicking with it. Once a Redstone signal is applied, the Tinkerer will switch the Augment applied to an adjacent Spark with the Augment inside its inventory slot. If left empty, it will simply remove the Augment on the Spark it is interacting with instead of switching it. Similarly, if the Spark has no Augment, it will simply add its Augment to the Spark.

If there are valid Sparks on multiple sides of the Tinkerer, it will randomly choose one of them with a different Augment than the one in its inventory each time a Redstone signal is applied. The Tinkerer's inventory can interact with Hoppers and other piping systems. A Redstone Comparator next to the Tinkerer will emit a signal based on the type of Augment currently stored.
