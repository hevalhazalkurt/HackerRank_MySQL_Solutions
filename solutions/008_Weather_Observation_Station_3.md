# 008 - Weather Observation Station 3

<br>

## Problem

Query a list of `CITY` names from `STATION`


## Input Format

The `STATION` table is described as follows :

![](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)

where `LAT_N` is the northern latitude and `LONG_W` is the western longitude.
---

## Solution


```SQL
SELECT DISTINCT CITY FROM STATION WHERE ID % 2 = 0
```

<br>

**Output**

```
Aguanga
Alba
Albany
Amo
Andersonville
Archie
Athens
Atlantic Mine
Bainbridge
Baker
Bass Harbor
Bayville
Beaufort
Bellevue
Benedict
Bennington
Bentonville
Biggsville
Bison
Bono
Bowdon
Bridgton
Brownsdale
Brownstown
Bullhead City
Busby
Cahone
Calhoun
Cannonsburg
Canton
Carver
Centertown
Cherry
Cheswold
Chignik Lagoon
Childs
Chilhowee
Chokio
Church Creek
Clancy
Climax
Clio
Clovis
Clutier
Coaling
Cobalt
Compton
Crane Lake
Cromwell
Crouseville
Curdsville
Daleville
Decatur
Deep River
Delano
Delray Beach
Delta
Dryden
Dumont
Dundee
East Haddam
East Irvine
Eastlake
Effingham
Elkton
Elm Grove
Ermine
Eros
Eskridge
Eufaula
Eustis
Everton
Farmington
Firebrick
Five Points
Forest
Forest Lakes
Fort Lupton
Frankfort Heights
Franklin
Gales Ferry
Garden City
Garland
Glen Carbon
Glencoe
Gorham
Grand Terrace
Grandville
Grapevine
Grayslake
Greens Fork
Greenview
Greenway
Grosse Pointe
Gustine
Hackleburg
Hampden
Hanscom Afb
Harmony
Haverhill
Hayfork
Hayneville
Healdsburg
Henderson
Heyburn
Holbrook
Hope
Howard Lake
Jolon
Julian
Kanorado
Kell
Kenner
Keyes
Kirkland
Kirksville
Kismet
Kissee Mills
Knobel
Larkspur
Leakesville
Leavenworth
Ledyard
Lee
Lismore
Little Rock
Loma Mar
Lottie
Ludington
Ludlow
Lupton
Lynnville
Macy
Magnolia
Manchester
Many
Marine On Saint Croix
Marion Junction
Mc Henry
Mcbrides
Mccomb
Melber
Mesick
Mid Florida
Middleboro
Millville
Mineral Point
Monroe
Montgomery City
Montrose
Morenci
Mosca
Mullan
Napoleon
Neon
New Ross
Newton Center
Norphlet
Norris
Norris City
North Berwick
North Monmouth
Norvell
Norwood
Oakfield
Oconee
Onaway
Orange City
Orange Park
Osage City
Ottertail
Ozona
Palatka
Palm Desert
Paron
Pattonsburg
Peachtree City
Pheba
Philipsburg
Pico Rivera
Pine Bluff
Pine City
Pleasant Grove
Pony
Prairie Du Rocher
Prince Frederick
Randall
Rantoul
Ravenden Springs
Raymondville
Regina
Richland
Robertsdale
Rocheport
Rockton
Rogers
Round Pond
Roy
Rumsey
Rydal
Saint Paul
Saint Petersburg
Salem
Schleswig
Seward
Sherrill
Shingletown
Shreveport
Siler
Sizerock
Skanee
South Britain
South Haven
Southport
Strasburg
Sturdivant
Taft
Tarzana
Tipton
Turners Falls
Ukiah
Vulcan
Walnut
Watkins
West Baden Springs
West Hills
West Hyannisport
White Horse Beach
Wickliffe
Winter Park
Yalaha
Yazoo City
Yellow Pine
Yuma
Zachary
```
