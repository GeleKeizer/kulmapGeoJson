kulmapGeoJson
=============

Adding classrooms to the geojson file
-------------------------------------

Add "rooms" to the properties list. Add one entry per floor like so: "[FLOOR_NAME]" : "[ROOMS]".

The [rooms] formatting rules:
- [ROOMS] == [ROOM1],[ROOM2],[ROOM3] where [ROOM1] == [ROOM], [ROOM2] == [ROOM], [ROOM3] == [ROOM]
- [ROOM] == \[NAME\] ([ROOM_NB])|[ROOM_TAG1]|[ROOM_TAG2]|