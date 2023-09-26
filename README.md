# pb-vehiclekeys

## Config

Config.UnloadEvent = 'QBCore:Client:OnPlayerUnload' -> Event trigged on player unload (default qb-core and qbx-core)

Config.LoadEvent = 'QBCore:Client:OnPlayerLoaded' -> Event trigged on player load (default qb-core and qbx-core)

## Exports

GiveKeys(plate, id) -> Give keys to vehicle of the plate to the player with the id (if id is nil then add to yourself)

HaveKeys(plate) -> Check if client have the key for vehicle with the plate

RemoveAllKeys -> Clean all client keys

GetAllCSNKeys -> Give back all keys that player character had in past
