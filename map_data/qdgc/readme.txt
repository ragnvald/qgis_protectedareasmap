QDGC level 1  	Tanzania, United Republic of [tza]
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - 


QDGC - Quarter Degree Grid Cells (or QDS - Quarter degree Squares) are a way of dividing the longitude latitude degree square cells into smaller squares, forming in effect a system of geocodes. QDGC represents a way of making (almost) equal area squares covering a specific area to represent specific qualities of the area covered. The squares themselves are based on the degree squares covering earth. Around the equator we have 360 longitudal lines lines, and from the north to the south pole we have 180 latitudal lines. Together this gives us 64800 segments or tiles covering earth.

Each degree square is designated by a full reference to the main degree square. S01E010 is a reference to a square in Tanzania. S means the square is south of equator, and E means it is East of the zero meridian. The numbers refeer to longitudal and latitudal degree.

A square with no sublevel reference is also called QDGC level 0. This is square based on a full degree longitude by a full degree latitude. The QDGC level 0 squares are themselves divided into four giving us level 1 size squares.

	AB
	CD

To get smaller squares the above squares are again divided in four - giving us a total of 16 squares within a degree square. The names for the new level of squares are named the same way. The full reference of a square could then be:

 * S01E010AD

On level 2 the 16 individual squares would look like this:

	AA AB BA BB

	AC AD BC BD

	CA CB DA DB

	CC CD DC DD


* * * * * * * * * * * * * * * * * * * * 
To facilitate the identification of the squares and ease the use of them in different contexts several attributes are provided with the files:

ARAEA		Calculated with XTools
		Km2, projected Coordinate System type, 
		Albers Equal-Area Conic Projection 
		(ref: ArcGIS and Wikipedia
		http://en.wikipedia.org/wiki/Albers_projection)

QDGC		level 1

LON_C		Shape centerpoint calculated With XTools

LAT_C		Shape centerpoint calculated With XTools

LON_NW		Square north-western longitude

LAT_NW		Square north-western latitude

LON_NE		Square north-eastern longitude

LAT_NE		Square north-eastern latitude

LON_SE		Square south-eastern longitude

LAT_SE		Square south-eastern latitude

LON_SW		Square south-western longitude

LAT_SW		Square south-western latitude



* * * * * * * * * * * * * * * * * * * * 
Layer Spatial Reference System

+proj=longlat +ellps=WGS84 +datum=WGS84 +no_defs



* * * * * * * * * * * * * * * * * * * * 
Coverage

This shapefile set covers all QDGC level one squares intersecting with the country area. The country code is based on the three letter country codes as defined in ISO 3166-1 alpha-3.



* * * * * * * * * * * * * * * * * * * * 
Read more here

* http://www.qdgc.org
* http://en.wikipedia.org/wiki/QDGC



* * * * * * * * * * * * * * * * * * * * 
Copyright

GNU GPL License is the closest one. Free of charge, free to use, free to change and free to distribute.



* * * * * * * * * * * * * * * * * * * * 
Conditions

Delivered to the user as-is. No guarantees. If you find errors, please tell and I will try to fix it.




* * * * * * * * * * * * * * * * * * * * 
Thanks for help and support

TAWIRI			http://www.tawiri.org
Dept of Biology, NTNU	http://www.bio.ntnu.no
Mindland consulting	http://www.mindland.com
Julian Blanc



Regards,

Ragnvald Larsen

ragnvald@mindland.com
NTNU/TAWIRI/Mindland consulting