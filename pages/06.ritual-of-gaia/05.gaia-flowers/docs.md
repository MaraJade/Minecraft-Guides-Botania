---
title: 'Gaia Flowers'
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

### Dandelifeon
Active mana generating flower, this is the most complex and most rewarding of the mana generating options. Following the basic principles of Conway's Game of Life, a 2D simulation of the life cycle of cells, this flower produces mana from Cellular Blocks that reach the 1 block range of the flower in the centre of the board. Before attempting to use this flower, a basic understanding of Conway's Game of Life is recommended.

The board is a 25x25 square area centred on the block the Dandelifeon is planted on. The board is two-dimensional, all rules will be played out on the same y-axis as the Dandelifeon. The flower must be provided with a Redstone signal to start the game, as long as the flower has a Redstone signal the game will progress at 2 steps per second. Each block on the board is a live Cell or a dead Cell. Live Cells are represented by Cellular Blocks, dead Cells are represented by empty air blocks. Live Cells can not be created in a space occupied by anything other than an air block. Live Cells have a starting age of zero. Age zero cells do not produce mana. Neighbours are the eight blocks surrounding any block on the board. All transitions during each step of the game occur simultaneously.

The game process includes the rules of Conway's Game of Life with a few modifications. During each step, the following transitions will occur:

1. Any live Cell with fewer than two or more than three live neighbours dies.
2. Any live Cell with exactly two or three live neighbours lives and its age increases by one.
3. Any dead Cell with exactly three live neighbours becomes a live Cell with age equal to the age of the oldest neighbour plus one.
4. Any live Cell with age greater than sixty dies.

When any live Cell would exist in the 3x3 area in the centre of the board, all Cells in that area are absorbed by the Dandelifeon and converted to mana. All cells elsewhere on the board die. Any Cell affected by multiple Dandelifeons or moved by any other means than the Dandelifeon itself will die.

### Shulk Me Not
An active mana producing flower, which produces large amounts of mana by "Harnessing the power of Levitation effect". When a hostile mob is hurt by a Shulker, the Shulk Me Not will kill both the Shulker and the mob, and produce mana. Both of them must be within the range of the flower, and all their drops will be deleted.
