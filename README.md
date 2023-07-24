# qb-spawn
Fully remade qb-spawn. 

Fully free qb-spawn for your qbcore server. Replacement of qb-spawn

![Untitled-1](https://github.com/QBCoreStore/qb-spawn/assets/68699717/877a4150-08f4-4207-a58c-9356ca058c83)

----------------------------------------------------------------------------------------------------------------------

Installation: 

1. Drag Drop to the resources folder.

2. Add this line in the qb-apartments > config.lua
----------------------------------------------------------------------------------------------------------------------

Apartments = {}
Apartments.Starting = true
Apartments.SpawnOffset = 30

-- target = true
Apartments.UseTarget = true


Apartments.Locations = {
    ["apartment1"] = {
        name = "apartment1",
        label = "South Rockford Drive",
        coords = {
            enter = vector4(-667.02, -1105.24, 14.63, 242.32),
        },
        pos = {top = 57, left = 32},
        polyzoneBoxData = {
            heading = 245,
            minZ = 13.5,
            maxZ = 16.0,
            debug = false,
            length = 1,
            width = 3,
            distance = 2.0,
            created = false
        },
		price = 600,
    },
    ["apartment2"] = {
        name = "apartment2",
        label = "Morningwood Blvd",
        coords = {
            enter = vector4(-1288.52, -430.51, 35.15, 124.81),
        },
        pos = {top = 67, left = 36},
        polyzoneBoxData = {
            heading = 124,
            minZ = 34.0,
            maxZ = 37.0,
            debug = false,
            length = 1,
            width = 3,
            distance = 2.0,
            created = false
        },
		price = 600,
    },
    ["apartment3"] = {
        name = "apartment3",
        label = "Integrity Way",
        coords = {
            enter = vector4(269.73, -640.75, 42.02, 249.07),
        },
        pos = {top = 48, left = 33.5},
        polyzoneBoxData = {
            heading = 250,
            minZ = 40,
            maxZ = 43.5,
            debug = false,
            length = 1,
            width = 1,
            distance = 2.0,
            created = false
        },
		price = 600,
    },
    ["apartment4"] = {
        name = "apartment4",
        label = "Tinsel Towers",
        coords = {
            enter = vector4(-619.29, 37.69, 43.59, 181.03),
        },
        pos = {top = 58, left = 39},
        polyzoneBoxData = {
            heading = 180,
            minZ = 41.0,
            maxZ = 45.5,
            debug = false,
            length = 1,
            width = 2,
            distance = 2.0,
            created = false
        },
		price = 600,
    },
    ["apartment5"] = {
        name = "apartment5",
        label = "Fantastic Plaza",
        coords = {
            enter = vector4(291.517, -1078.674, 29.405, 270.75),
        },
        pos = {top = 48, left = 31},
        polyzoneBoxData = {
            heading = 270,
            minZ = 28.5,
            maxZ = 31.0,
            debug = false,
            length = 1,
            width = 2,
            distance = 2.0,
            created = false
        },
		price = 600,
    },
}
