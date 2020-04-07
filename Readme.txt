UESP TramrielRebuilt Map
by Anonytroll & Seneca37 (anonytroll@hotmail,  & seneca37_y@yahoo.com)


This map was developed from Dave Humphrey's UESP Game Maps.

As of 21/11/15 (Nov 21, 2015)

The following files were NOT modifed
   cellresource.js
   flatprojection.js
   infobox.js
   label.js
   map2.css
   map2mobile.css
   mapstate.js
   map_edit.js
   map_noedit.js
   markerwithlabel.js

The following files have been modifed.
   getmaplocs.php  = fixed dbname
   location.js = removed encodeURIComponent from function umMakeInnerLocationInfoContent
   map2.js  = updated umGetMapTile
   search.js = removed encodeURIComponent from function umCreateSearchResultText
   setmaplocs.php  = updated database name & removed $game code
   smallmaphelp.html  = removed erroneous comments
   trmap2.js  = updated variables for TR map & updated Icons for TR map
   UespMemcachedSession.php
       = Added $uespMaps... variables at top associated with the database
       = Updated UESP_ contants associated with the database.



