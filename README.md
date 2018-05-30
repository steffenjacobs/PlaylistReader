# PlaylistReader
This small tool can read a playlist and copy all related files into a new directory. This is useful e.g. if you use playlists on your computer and wants to copy all files from a playlist to your mobile phone.

# Usage
java -jar ./PlaylistReader.jar &lt;Path-To-PlaylistFile1&gt; [&lt;PlaylistFile2&gt;]*

It is possible to add multiple playlist files, separated by spaces.

# How it works
First, the tool will create a new directory in the same folder, the playlist file is in. The directory will be named after the playlist. 
The tool will then retrieve the file associated to each entry in the playlist and copies it into the new directory.
