[Jaanga]( http://jaanga.github.io/ ) &raquo; [Moon]( http://jaanga.github.io/moon/ )

[moon-heightmaps-256p-ne Read Me]( index.html )
===
This repository contains 10,800 PNGs that provide height data for the Moon for latitudes -1 to -60 and longitude -1 to -180


<span style=display:none; >[You are now in GitHub source code view - click here to view Read Me file as a web page]( http://jaanga.github.io/moon/moon-heightmaps-256p-ne/ "View file as a web page." ) </span>
<input type=button value='You are now in GitHub web page view - Click here to view Read Me file as source code' onclick=window.location.href='https://github.com/jaanga/moon/tree/gh-pages/moon-heightmaps-256p-ne/'; />

## Sample Use of Data in 3D App
<iframe src="http://jaanga.github.io/moon/rover-256p/moon-rover-256p-multi-tile-r1.html" width=100% height=500px ></iframe>  
####_Moon Rover 256P - Dev revision_

[Moon Rover 256P Code Edit View Fullscreen]( http://exploratoria.github.io/lib/code-edit-view/code-edit-view.html#http://jaanga.github.io/moon/rover-256p/moon-rover-256p-multi-tile-r1.html )

[Moon Rover 256P Demo Full Screen - Dev]( http://jaanga.github.io/moon/rover-256p/dev/ )

This demo uses heightmap data to:

* To display the Moon in as much 3D detail as possible
* To enable you to explore craters and the dark side and more


## Sample Use of Data on Remote Web Site
_May take a while to load. Page freezes while loading..._

<iframe src="http://jsfiddle.net/theo/dwje1w0d/" width=100% height=500px ></iframe>  
#### _Read PNG Composite R2 hosted on jsFiddle_


[Read multiple PNG files and combine]( http://jaanga.github.io/moon/utilities/read-png-composite-r2.html> )

* Combines multiple heightmap PNG files into one view
* Use cursor keys to navigate
* Edit parameters in the code or use permalinks

Data hosted on GitHub pages is CORS-compatible and may therefor be accessed from any web site or server.
The example above access the heightmap data on GitHub from an HTL file hosted on [jsFiddle]( http://jasfiddle.net ).



## File information Info


### Data from first line of file WAC_GLD100_E300N0450_256P.IMG

	PDS_VERSION_ID = PDS3

	/* The source image data definition. */
	RECORD_TYPE = FIXED_LENGTH
	RECORD_BYTES = 46080
	FILE_RECORDS = 15361
	LABEL_RECORDS = 1
	^IMAGE = 2

	/* Identification Information */
	DATA_SET_ID = "LRO-L-LROC-5-RDR-V1.0"
	DATA_SET_NAME = "LRO MOON LROC 5 RDR V1.0"
	VOLUME_ID = 'LROLRC_2001'
	PRODUCER_INSTITUTION_NAME = "ARIZONA STATE UNIVERSITY"
	PRODUCER_ID = LRO_LROC_TEAM
	PRODUCER_FULL_NAME = "MARK ROBINSON, PH.D"
	PRODUCT_ID = "WAC_GLD100_E300N0450_256P"
	PRODUCT_VERSION_ID = "v1.2"
	PRODUCT_TYPE = "RDR"
	INSTRUMENT_HOST_NAME = "LUNAR RECONNAISSANCE ORBITER"
	INSTRUMENT_HOST_ID = "LRO"
	INSTRUMENT_NAME = "LUNAR RECONNAISSANCE ORBITER CAMERA"
	INSTRUMENT_ID = "LROC"
	TARGET_NAME = MOON
	MISSION_PHASE_NAME = ("NOMINAL MISSION", "SCIENCE MISSION")
	RATIONALE_DESC = "Created at the request of NASA's Exploration
	Systems Mission Directorate to support future
	human exploration"
	SOFTWARE_NAME = "DLR Software Suite with ISIS 3.2.1"

	/* Time Parameters */
	START_TIME = "N/A"
	STOP_TIME = "N/A"
	SPACECRAFT_CLOCK_START_COUNT = "N/A"
	SPACECRAFT_CLOCK_STOP_COUNT = "N/A"
	PRODUCT_CREATION_TIME = 2011-11-14T22:05:42

	/* NOTE: */
	/* This raster image is composed of a set of pixels that represent finite */
	/* areas, and not discrete points. The center of the upper left pixel is */
	/* defined as line and sample (1.0,1.0). The */
	/* [LINE,SAMPLE]_PROJECTION_OFFSET elements are the pixel offset from line */
	/* and sample (1.0,1.0) to the map projection origin (defined by the */
	/* CENTER_LATITUDE and CENTER_LONGITUDE elements). These offset values */
	/* are positive when the map projection origin is to the right or below */
	/* the center of the upper left pixel. This definition was adopted in */
	/* November 2011 by the LROC team. */

	OBJECT = IMAGE_MAP_PROJECTION
	^DATA_SET_MAP_PROJECTION = "DSMAP.CAT"
	MAP_PROJECTION_TYPE = EQUIRECTANGULAR
	PROJECTION_LATITUDE_TYPE = PLANETOCENTRIC
	A_AXIS_RADIUS = 1737.4 <KM>
	B_AXIS_RADIUS = 1737.4 <KM>
	C_AXIS_RADIUS = 1737.4 <KM>
	COORDINATE_SYSTEM_NAME = PLANETOCENTRIC
	POSITIVE_LONGITUDE_DIRECTION = EAST
	KEYWORD_LATITUDE_TYPE = PLANETOCENTRIC
	/* NOTE: CENTER_LATITUDE and CENTER_LONGITUDE describe the location */
	/* of the center of projection, which is not necessarily equal to the */
	/* location of the center point of the image. */
	CENTER_LATITUDE = 0 <DEG>
	CENTER_LONGITUDE = 0 <DEG>
	LINE_FIRST_PIXEL = 1
	LINE_LAST_PIXEL = 15360
	SAMPLE_FIRST_PIXEL = 1
	SAMPLE_LAST_PIXEL = 23040
	MAP_PROJECTION_ROTATION = 0.0 <DEG>
	MAP_RESOLUTION = 256.00000000001 <PIX/DEG>
	MAP_SCALE = 118.45058759433 <METERS/PIXEL>
	MAXIMUM_LATITUDE = 60.0 <DEG>
	MINIMUM_LATITUDE = 0.0 <DEG>
	EASTERNMOST_LONGITUDE = 90.0 <DEG>
	WESTERNMOST_LONGITUDE = 0.0 <DEG>
	LINE_PROJECTION_OFFSET = 15359.500000001 <PIXEL>
	SAMPLE_PROJECTION_OFFSET = -0.5 <PIXEL>
	END_OBJECT = IMAGE_MAP_PROJECTION

	OBJECT = IMAGE
	DESCRIPTION = "The Global Lunar DTM 100 m topographic model
	(GLD100) is derived from images acquired with
	the LROC Wide Angle Camera"

	LINES = 15360
	LINE_SAMPLES = 23040
	SAMPLE_TYPE = LSB_INTEGER
	SAMPLE_BITS = 16
	SAMPLE_BIT_MASK = 2#1111111111111111#
	CORE_NULL = -32768
	CORE_LOW_REPR_SATURATION = -32767
	CORE_LOW_INSTR_SATURATION = -32766
	CORE_HIGH_REPR_SATURATION = -32764
	CORE_HIGH_INSTR_SATURATION = -32765

	BAND_STORAGE_TYPE = BAND_SEQUENTIAL
	BANDS = 1

	END_OBJECT = IMAGE
	END


### From [http://wms.lroc.asu.edu/lroc/view_rdr/WAC_GLD100]( http://wms.lroc.asu.edu/lroc/view_rdr/WAC_GLD100 )

The WAC Digital Terrain Model (DTM) was constructed from WAC stereo images. This new map is called the Global Lunar DTM 100 m topographic model, or "GLD100", and covers 98.2% of the lunar surface. Using digital photogrammetric techniques the GLD100 was computed from 69,000 WAC stereo models. Due to persistent shadows near the poles it is not possible to create a complete WAC stereo map at the very highest latitudes. The GLD100 thus covers from 79° S latitude to 79° N latitude. Since the stereo correlation box is bigger than 100 meters, surface details at the 100-meter scale are not fully resolved. However, each 100-meter square has an average of 26 stereo points within it (for a planet-wide total of 100 billion points), which helps to sharpen the elevation estimate. The resolution, in a formal sense, is probably close to 300 meters, and the accuracy of the elevations is estimated to be about 10 to 20 meters (Scholten et al JGR in press).

The GLD100 is available in the original 100 meters/pixel scale format in ten tiles. The GLD100 is also available in same tile format for scales of 256 pixels per degree (ppd) and 128 ppd. The LRO Lunar Orbiter Laser Altimeter (LOLA) excels at characterizing the topography of the poles. Since the LRO orbits converge at the poles LOLA provides a very high resolution topographic model of the poles. For the 256 ppd and lower resolution formats the LOLA polar data fills in the WAC "hole at the pole".

The WAC topography was produced by LROC team members at the German Aerospace Center (DLR).



## Copyright and License

Copyright © 2015 Jaanga authors

This work is available under two licenses

1: Jaanga software is available under the [MIT License]( http://en.wikipedia.org/wiki/MIT_License) which states:

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'),
to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

The software is provided 'as is', without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement.
In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.


2: Jaanga data is available under a Creative Commons license

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/StillImage" rel="dct:type">work</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.


