### download (youtube video) bash script

This is a script that automatically downloads a portion of a youtube video using yt-dlp.

### Installation

First, make sure you have yt-dlp downloaded
`brew install yt-dlp`

Then copy the 'download' bash script into your /bin/bash directory.

Call it 'download', if you like.

Then you need to give it permissions to run.

`chmod +x /path/to/download`

### Usage

You can either enter all of the info in one line in the following order:
`download "[link]" "[start time]" "[end time]" "[file name]"`

or you can simply type `download` with no arguments and you will be prompted for the link, start and end times, and target file name one at a time.

To see these options in the command line type `download -h`

### Notes

`downloadp` forces you only to use the *prompting* system. `download` does both based on number of args given
