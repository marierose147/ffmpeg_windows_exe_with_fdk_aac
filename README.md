FFmpeg README
=============

FFmpeg is a collection of libraries and tools to process multimedia content
such as audio, video, subtitles and related metadata.

## Libraries

* `libavcodec` provides implementation of a wider range of codecs.
* `libavformat` implements streaming protocols, container formats and basic I/O access.
* `libavutil` includes hashers, decompressors and miscellaneous utility functions.
* `libavfilter` provides a mean to alter decoded Audio and Video through chain of filters.
* `libavdevice` provides an abstraction to access capture and playback devices.
* `libswresample` implements audio mixing and resampling routines.
* `libswscale` implements color conversion and scaling routines.

## Tools

* [ffmpeg](https://ffmpeg.org/ffmpeg.html) is a command line toolbox to
  manipulate, convert and stream multimedia content.
* [ffplay](https://ffmpeg.org/ffplay.html) is a minimalistic multimedia player.
* [ffprobe](https://ffmpeg.org/ffprobe.html) is a simple analysis tool to inspect
  multimedia content.
* Additional small tools such as `aviocat`, `ismindex` and `qt-faststart`.

## Documentation

The online documentation is available in the main [website](https://ffmpeg.org)
and in the [wiki](https://trac.ffmpeg.org).

## License

FFmpeg codebase is mainly LGPL-licensed with optional components licensed under
GPL. Please refer to the LICENSE file for detailed information.

## Contributing

Patches should be submitted to the ffmpeg-devel mailing list using
`git format-patch` or `git send-email`. Github pull requests should be
avoided because they are not part of our review process and will be ignored.

## Configuration
```
ffmpeg version n5.0-ffmpeg-windows-build-helpers Copyright (c) 2000-2022 the FFmpeg developers
  built with gcc 10.2.0 (GCC)
  configuration: --pkg-config=pkg-config --pkg-config-flags=--static --extra-version=ffmpeg-windows-build-helpers --enable-version3 --disable-debug --disable-w32threads --arch=x86_64 --target-os=mingw32 --cross-prefix=/home/runner/ffmpeg-windows-build-helpers/sandbox/cross_compilers/mingw-w64-x86_64/bin/x86_64-w64-mingw32- --enable-libcaca --enable-gray --enable-libtesseract --enable-fontconfig --enable-gmp --enable-gnutls --enable-libass --enable-libbluray --enable-libbs2b --enable-libflite --enable-libfreetype --enable-libfribidi --enable-libgme --enable-libgsm --enable-libilbc --enable-libmodplug --enable-libmp3lame --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopus --enable-libsnappy --enable-libsoxr --enable-libspeex --enable-libtheora --enable-libtwolame --enable-libvo-amrwbenc --enable-libvorbis --enable-libwebp --enable-libzimg --enable-libzvbi --enable-libmysofa --enable-libopenjpeg --enable-libopenh264 --enable-liblensfun --enable-libvmaf --enable-libsrt --enable-libxml2 --enable-opengl --enable-libdav1d --enable-cuda-llvm --enable-libsvthevc --enable-libsvtav1 --enable-libaom --enable-libvpx --enable-nvenc --enable-nvdec --extra-libs=-lharfbuzz --extra-libs=-lm --extra-libs=-lpthread --extra-cflags=-DLIBTWOLAME_STATIC --extra-cflags=-DMODPLUG_STATIC --extra-cflags=-DCACA_STATIC --enable-amf --enable-libmfx --enable-gpl --enable-frei0r --enable-librubberband --enable-libvidstab --enable-libx264 --enable-libx265 --enable-avisynth --enable-libaribb24 --enable-libxvid --enable-libdavs2 --enable-libxavs2 --enable-libxavs --extra-cflags='-mtune=generic' --extra-cflags=-O3 --enable-static --disable-shared --prefix=/home/runner/ffmpeg-windows-build-helpers/sandbox/cross_compilers/mingw-w64-x86_64/x86_64-w64-mingw32 --enable-nonfree --enable-libfdk-aac --enable-decklink
  libavutil      57. 21.100 / 57. 21.100
  libavcodec     59. 20.100 / 59. 20.100
  libavformat    59. 17.101 / 59. 17.101
  libavdevice    59.  5.100 / 59.  5.100
  libavfilter     8. 26.101 /  8. 26.101
  libswscale      6.  5.100 /  6.  5.100
  libswresample   4.  4.100 /  4.  4.100
  libpostproc    56.  4.100 / 56.  4.100

  configuration:
    --pkg-config=pkg-config --pkg-config-flags=--static
    --extra-version=ffmpeg-windows-build-helpers
    --enable-version3
    --disable-debug
    --disable-w32threads
    --arch=x86_64
    --target-os=mingw32
    --cross-prefix=/home/runner/ffmpeg-windows-build-helpers/sandbox/cross_compilers/mingw-w64-x86_64/bin/x86_64-w64-mingw32-
    --enable-libcaca
    --enable-gray
    --enable-libtesseract
    --enable-fontconfig
    --enable-gmp
    --enable-gnutls
    --enable-libass
    --enable-libbluray
    --enable-libbs2b
    --enable-libflite
    --enable-libfreetype
    --enable-libfribidi
    --enable-libgme
    --enable-libgsm
    --enable-libilbc
    --enable-libmodplug
    --enable-libmp3lame
    --enable-libopencore-amrnb
    --enable-libopencore-amrwb
    --enable-libopus
    --enable-libsnappy
    --enable-libsoxr
    --enable-libspeex
    --enable-libtheora
    --enable-libtwolame
    --enable-libvo-amrwbenc
    --enable-libvorbis
    --enable-libwebp
    --enable-libzimg
    --enable-libzvbi
    --enable-libmysofa
    --enable-libopenjpeg
    --enable-libopenh264
    --enable-liblensfun
    --enable-libvmaf
    --enable-libsrt
    --enable-libxml2
    --enable-opengl
    --enable-libdav1d
    --enable-cuda-llvm
    --enable-libsvthevc
    --enable-libsvtav1
    --enable-libaom
    --enable-libvpx
    --enable-nvenc
    --enable-nvdec
    --extra-libs=-lharfbuzz
    --extra-libs=-lm
    --extra-libs=-lpthread
    --extra-cflags=-DLIBTWOLAME_STATIC
    --extra-cflags=-DMODPLUG_STATIC
    --extra-cflags=-DCACA_STATIC
    --enable-amf
    --enable-libmfx
    --enable-gpl
    --enable-frei0r
    --enable-librubberband
    --enable-libvidstab
    --enable-libx264
    --enable-libx265
    --enable-avisynth
    --enable-libaribb24
    --enable-libxvid
    --enable-libdavs2
    --enable-libxavs2
    --enable-libxavs
    --extra-cflags='-mtune=generic'
    --extra-cflags=-O3
    --enable-static
    --disable-shared
    --prefix=/home/runner/ffmpeg-windows-build-helpers/sandbox/cross_compilers/mingw-w64-x86_64/x86_64-w64-mingw32
    --enable-nonfree
    --enable-libfdk-aac
    --enable-decklink
```

## About automatic build

Each time you mark a star, it will be automatically built once. Please download the latest build file from [GitHub Actions](https://github.com/marierose147/ffmpeg_windows_exe_with_fdk_aac/actions).

