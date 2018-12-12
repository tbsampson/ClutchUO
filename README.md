# [ServUO]

[![Travis Build Status](https://travis-ci.org/ServUO/ServUO.svg)](https://travis-ci.org/ServUO/ServUO)

ServUO is a community driven Ultima Online Server Emulator written in C#.

### Website

https://www.servuo.com

### Installation

Getting started with ServUO is quite easy.

#### Windows

Just run `Compile.WIN - Debug.bat` and follow the prompts. This script will compile both the server binary and Ultima SDK binary for you and run the server for you at end. 

Run `Compile.WIN - Debug.bat` for development, attaching a debugger and/or extended output.

Run `Compile.WIN - Release.bat` for production environment (-debug is still a supported parameter for script debugging).

After this you can run the server by executing `ServUO.exe`.
#### Debian 9.x
'git clone git@github.com:ServUO/ServUO.git'

'cd ServUO'

`apt install apt-transport-https dirmngr`
`apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF`
`echo "deb https://download.mono-project.com/repo/debian stable-stretch main" | sudo tee /etc/apt/sources.list.d/mono-official-stable.list`
`apt update`
`apt install mono-complete`

'make clean'
'make'

'./ServUO.sh'

Complete guide is available here:
https://www.servuo.com/tutorials/yet-another-debian-servuo-tutorial.44/

#### OSX

`brew install mono`  
`make`

#### Ubuntu

`apt-get install mono-complete`  
`make`

A quick start guide is available at our forums. Follow this link: [Quickstart]

### Development

Want to contribute? Great!

You can submit a pull request at any time and we will review it asap!

License
----

GPL v2




   [ServUO]: <https://www.servuo.com>
   [Quickstart]: <https://www.servuo.com/tutorials/getting-started-with-servuo.2/>
