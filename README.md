FLAC to iTunes
==============

A simple automator workflow to import FLAC files to iTunes.

*Note: The flac2mp3 script was removed from the "flac" homebrew package, so these instructions are incomplete. I'll get an update out soon, but in the meantime, a workaround is to install the [flac2mp3 script](https://github.com/rmndk/flac2mp3) to a folder on your PATH.*

 1. Install [Homebrew](http://brew.sh/).
 2. From the command prompt, run `brew install flac`
 3. Create a "FLAC to iTunes" folder. I use ~/Music/FLAC to iTunes.
 4. Add this workflow as a folder action on your "FLAC to iTunes" folder.
 5. Move FLAC files into that folder. The FLAC files will be converted to MP3s and deleted. The MP3s will be imported into iTunes.

*Note: This will delete the FLAC files that you move into that folder. Use caution.*
