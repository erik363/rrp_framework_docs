# RRP Framework Spawner

## OwnedVehicle(plate, coords, warp)

Spawns a vehicle that is owned by a player. 

### Parameters:
- `plate` (string): The license plate of the vehicle.
- `coords` (vec4): The coordinates where the vehicle will spawn.
- `warp` (bool, optional): If true, the player will warp into the vehicle after it has spawned. Defaults to false.

### Example Usage:

```lua
RRP.Spawner.OwnedVehicle("ABC123", vector4(0,0,0,0), true)
