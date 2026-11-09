# MG5
## Devlog

1. NavMesh is more useful for autonomous navigation while scripting allows the player to have more control over the character's movement. Enemies that move towards the player should use a NavMesh to help it navigate our the terrain automatically to its desire location of the player. No player input is needed to handle this. While (non click-to-move) player controlled characters 
2.  Inside the loop, we index through `_birds` to get each bird. We check if the distance between the bird's position and player's position is less than `_interactDistance`, meaning we check if the player is close enough to the bird. If it is true (the player is close enough), it calls that bird's `RunAway()` function. Only the birds that are close enough to the player run away.


## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
