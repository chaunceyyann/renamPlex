renamPlex
=========

A renamer program for Plex media server.

*Series/Episode type TV Shows*

To name series/episode based shows:

TV Shows/Show_Name/Season XX/ShowName - sXXeYY - Optional_Info.ext
Where:

XX is the season number

YY is the episode number

Optional_Info is some additional optional information (e.g. episode title) and is ignored by Plex.

*Multi-Episode Files*

If a single file covers more than one episode, name it as follows:

TV Shows/Show_Name/Season XX/ShowName - sXXeYY-eZZ.ext

where ZZ is the last episode number contained in the file (e.g. "Heroes s04e01-e02.mkv" for two episodes)
