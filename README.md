# libretro-mpv-launcher
![mpv](https://github.com/new-penguin/libretro-mpv-launcher/assets/139792946/23dc2796-152b-4d23-9521-fd1a29eb8d9b)


Based on [libretro-dolphin-launcher](https://github.com/RobLoach/libretro-dolphin-launcher)

Launch videos with [RetroArch](http://www.libretro.com/) using [MPV](https://mpv.io/)


## Installation

Download the Linux core from releases and skip to step 2 or...

1. Compile the core
  ``` bash
  git clone https://github.com/new-penguin/libretro-mpv-launcher-antimicrox
  cd libretro-mpv-launcher
  make
  ```

2. Copy the core file to the RetroArch cores directory. For example, to copy to the default core directory. Controls are fairly intuitive, RS is exit.
  ``` bash
  cp mpv_launcher_libretro.so /usr/lib/libretro/mpv_launcher_libretro.so
  cp mpv_launcher_libretro.info /usr/share/libretro/info/mpv_launcher_libretro.info
  ```

3. Make sure mpv-full is installed because regular mpv doesn't have SDL2 support built in.


## Usage

1. Copy input.conf into your mpv config directory, normally ~/home/user/.config/mpv.

2. Import videos intro Retroarch.

3. Watch videos.

* To do: Possibly implement overlay and CRT shader so we can party like it's 1985.

## Contributors

- [Rob Loach](http://github.com/robloach)
- [Alcaro](https://github.com/Alcaro)
- [Eduardo Mozart de Oliveira](https://github.com/coldscientist)
