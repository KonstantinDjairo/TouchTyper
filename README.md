![Demo](https://j.gifs.com/16NGQP.gif)

![](https://github.com/siddharthroy12/TouchTyper/actions/workflows/nativebuild.yml/badge.svg)
![](https://github.com/siddharthroy12/TouchTyper/actions/workflows/webbuild.yml/badge.svg)
# About

I practice typing a lot and I've been using monkey type for long time but that website does not work smoothly on my low-end laptop and I can't use it when I don't have internet so I made my own typing test program using C++.

You can download it from the [releases](https://github.com/siddharthroy12/TouchTyper/releases) page or just visit the [website](https://touchtyper.netlify.app/) to run it on your browser.

# Build Instructions

## Building for Web

**You need to install Emscripten** [Download Here!](https://emscripten.org/docs/getting_started/downloads.html)

1. Clone the repository using Git. Execute this in a terminal: `git clone https://github.com/siddharthroy12/TouchTyper`
1. Cd into TouchTyper. `cd TouchTyper`
1. Install the raylib git submodule using `git submodule update --init --recursive --depth=1`
1. Make a build folder. Your builds will go here. `mkdir build; cd build`
1. Setup cmake `emcmake cmake -S .. -D CMAKE_BUILD_TYPE=Release`
1. Run `cmake --build .` to compile the project
1. Run a local web server and open the TouchTyper.html

## Building (Unix)

1. Clone the repository using `git clone https://github.com/siddharthroy12/TouchTyper`
1. Move to the TouchTyper directory
`cd TouchTyper`
1. Install the raylib git submodule using `git submodule update --init --recursive --depth=1`
1. Make a build folder and cd to it with `mkdir build && cd build`
1. Setup cmake `cmake .. -DCMAKE_BUILD_TYPE=Release`
1. Run `make` to compile the project
1. Make the binary executable `chmod +x TouchTyper`
1. Run the binary with `./TouchTyper`


# License

Copyright (c) 2021-2022 Siddharth <br></br>
Copyright (c) 2023 Hashirama


This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see https://www.gnu.org/licenses/.
