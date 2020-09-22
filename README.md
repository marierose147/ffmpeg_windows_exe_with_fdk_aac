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
ffmpeg version n4.3.1-ffmpeg-windows-build-helpers Copyright (c) 2000-2020 the FFmpeg developers
built with gcc 10.1.0 (GCC)
configuration:
--enable-version3
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
--enable-libaribb24
--enable-demuxer=dash
--enable-libxml2
--enable-opengl
--enable-libdav1d
--enable-cuda-llvm
--enable-libaom
--enable-libvpx
--enable-nvenc
--enable-nvdec
--extra-libs=-lharfbuzz
--extra-libs=-lm
--extra-libs=-lpthread
--enable-amf
--enable-libmfx
--enable-gpl
--enable-frei0r
--enable-filter=frei0r
--enable-librubberband
--enable-libvidstab
--enable-libx264
--enable-libx265
--enable-libxvid
--enable-libdavs2
--enable-libxavs2
--enable-libxavs
--enable-avresample
--enable-static
--enable-nonfree
--enable-libfdk-aac
--enable-decklink
```

## About automatic build

Each time you mark a star, it will be automatically built once. Please download the latest build file from GitHub Actions.

