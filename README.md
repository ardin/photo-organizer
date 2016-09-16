# photo-organizer

Script extracts create date from exif metadata included in image file, then creates directory in format YYYY-MM and moves  file in new format YYYY-MM-DD_H:m:s.ext .

**Usage:**
<pre>
$ photo-organizer 
Syntax: photo-organizer < photo directory >
</pre>

**Example:**
<pre>
$ photo-organizer 2013
„2013/11/DSC_0001.jpg” -> „2013-11/2013-11-11_11:39:12.jpg”
„2013/11/DSC_0002.jpg” -> „2013-11/2013-11-11_11:40:04.jpg”
</pre>