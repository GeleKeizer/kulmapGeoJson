kulmapGeoJson
=============

Adding classrooms to the geojson file
-------------------------------------

Add "rooms" to the properties list. Add one entry per floor like so: "[FLOOR_NAME]" : "[ROOMS]".

The [rooms] formatting rules:
- [ROOMS] == [ROOM1],[ROOM2],[ROOM3] where [ROOM1] == [ROOM], [ROOM2] == [ROOM], [ROOM3] == [ROOM]
- [ROOM] == \[NAME\] ([ROOM_NB])|[ROOM_TAG1]|[ROOM_TAG2]|

Please, do not use spaces within || or within () (eg. to use "SOL N" as tag, do |sol|n|). Remark that \[NAME\] is not seen as tag, thus words used in \[NAME\], do also need to be added as tags.

See examples in kulmap.geojson.