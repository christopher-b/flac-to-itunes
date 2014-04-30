FLAC to iTunes
==============

A simple automator workflow to import FLAC files to iTunes. 

 1. Install [Homebrew](http://brew.sh/).
 2. From the command prompt, run `brew install flac`
 3. Create a "FLAC to iTunes" folder. The default is ~/Music/FLAC to iTunes.
 4. Add this workflow as a folder action on your "FLAC to iTunes" folder.
 5. Change the flac_bin variable in the workflow to a folder containing the flac binaries. You can find the folder by running `dirname \`which flac\`` on the command prompt.
 6. Move FLAC files into that folder. The FLAC files will be converted to MP3s and deleted. The MP3s will be imported into iTunes. 

*Note: This will delete the FLAC files that you move into that folder. Use caution.*
