# MP3 converter to 320kbps

This script converts any mp3 file to 320kbps quality.
The main goal for this script is that some car stereos only accepts .mp3 files that are at 320kbps of quality.
So, this script converts to a compatible format


## How to use?

- Clone the project
- Install the dependencies (linux):
> sudo apt update                                             
> sudo apt install ffmpeg
- Install the project dependencies:
> bundle install
- Run the project:
> <pre><font color="#42E66C">ruby</font> <u style="text-decoration-style:single">main.rb</u> <u style="text-decoration-style:single">[mp3 files folder]</u> <u style="text-decoration-style:single">[output folder]</u></pre>
- Command example:
> <pre><font color="#42E66C">ruby</font> <u style="text-decoration-style:single">main.rb</u> <u style="text-decoration-style:single">/home/paulo/Música</u> <u style="text-decoration-style:single">/home/paulo/Música/converted</u></pre>