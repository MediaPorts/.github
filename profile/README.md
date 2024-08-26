# Port libmpv for vcpkg

## The libraries listed below are missing from vcpkg, need porting with some patch fixes.
```
 libdvdread (can be port patches from https://github.com/ShiftMediaProject/libdvdread)
 libdvdnav (can be port patches from https://github.com/ShiftMediaProject/libdvdnav)
 libdvdcss (can be port patches from https://github.com/ShiftMediaProject/libdvdcss)
 libbluray (can be port patches from https://github.com/ShiftMediaProject/libbluray)
 libsoxr
 libzimg (with graphengine)
 libudfread
 libmysofa
 avisynth-headers
 libvpl
 libplacebo (with glad, fast_float, xxhash)
 libbs2b
 uavs3d
 davs2
 libsixel
 libdovi
 libva
 xvidcore (1.3.7)
 libzvbi
 svtav1
 libaribcaption
 vapoursynth (R65/R63)
```

## The libraries below are available in vcpkg, need testing whether their versions are compatible with libmpv.
```
 ANGLE
 FFmpeg
 x264
 x265
 uchardet
 rubberband (with libsamplerate)
 opus
 openal-soft
 luajit
 libvpx
 libwebp
 libpng
 libunibreak
 libass
 lcms2
 lame
 harfbuzz
 freetype2
 flac
 opus-tools
 mujs
 libarchive
 shaderc (with spirv-headers, spirv-tools, glslang)
 vulkan-header
 vulkan
 spirv-cross
 fribidi
 nettle
 curl
 libxml2
 amf-headers
 nvcodec-headers
 megasdk (with readline, cryptopp, sqlite, libuv, libsodium)
 aom
 dav1d
 libplacebo (with glad, fast_float, xxhash)
 fontconfig
 libssh
 libsrt
 libjxl (with brotli, highway)
 libmodplug
 zlib (zlib-ng)
 zstd
 expat
 openssl
 libsdl2
 speex
 vorbis
```

 ogg
 bzip2
 lzo (2.10)
 libopenmpt (0.7.8)
 libiconv (1.17)
