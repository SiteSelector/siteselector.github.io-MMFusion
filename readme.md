Download
--------

[FusionTablesSlider ][dl] -- 12 Jan 2014

[dl]: https://github.com/PiotrKrosniak/FusionTablesSlider/archive/master.zip


Introduction
------------

FusionTablesSlider is a simple script for using a JQuery slider to
change map layers from Google Fusion Tables.

[Visit Piotr GIS Works ][aa] my Blog, tutorials how to use this repo and much more.

[aa]: http://piotrgisworks.blogspot.com/ 

Make changes in index.html

Lines to change  
[3]Change title.
[13] This coordinates it's where your map will be centered
[16] Zoom level, optional to modified
[17-22] Map Controls (false/true) , optional to modified  
[29 & 39] Fusion table location column is an existing geocoded column of type Location. For example country names or county names, zip codes etc.
[30 & 40] Fusion Table ID, you can use FT Wizard to extract ID
[32-33 & 42-43] Fusion table style and template ID, you can use also Wizard.

TIP. You can add more layers just copy paste the code and name it as next layer ie. layer3, layer4. 

If you want to customize your slider change parameter in lines [76], below list of options based on 

[Visit Piotr GIS Works ]

DEMO
------------

[DEMO http://piotrkrosniak.github.io/] [bb]

[bb]: http://piotrkrosniak.github.io/
Slider style

<img src="http://4.bp.blogspot.com/-g3zU1lymAh4/UtJethU-StI/AAAAAAAAGfc/Ss-rMMf4ur4/s1600/Screenshot+from+2014-01-12+10:20:10.png"/>

Acknowledgements <a id="acknowledgements" />
----------------

  [ss]: http://loopj.com/jquery-simple-slider/

FusionTablesSlider uses James Smiths' [jQuery Simple Slider][ss]

[dl]: https://github.com/lucastimmons/FusionTablesScrubber/

FusionTablesSlider is based on Lucas Timmons [FusionTablesScrubber][dl]


