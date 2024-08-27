# Port libmpv for vcpkg

https://github.com/microsoft/vcpkg/pull/40587

## The libraries listed below are missing from vcpkg, need porting with some patch fixes.

 - [x] libdvdread
 - [x] libdvdnav
 - [x] libdvdcss
 - [x] libbluray
 - [x] libsoxr (https://gitlab.com/shinchiro/soxr/-/blob/master/CMakeLists.txt)
 - [ ] libzimg (with graphengine)
 - [ ] libudfread
 - [ ] libmysofa (https://github.com/microsoft/vcpkg/pull/38368)
 - [ ] avisynth-headers
 - [x] libvpl (https://github.com/intel/libvpl/blob/main/CMakeLists.txt)
 - [ ] libplacebo (with glad, fast_float, xxhash)
 - [ ] libbs2b
 - [x] uavs3d (https://github.com/uavs3/uavs3d/blob/master/CMakeLists.txt)
 - [ ] davs2
 - [ ] libsixel
 - [ ] libdovi
 - [ ] libva
 - [ ] xvidcore (1.3.7)
 - [ ] libzvbi
 - [x] svtav1 (https://gitlab.com/AOMediaCodec/SVT-AV1/-/blob/master/CMakeLists.txt)
 - [x] libaribcaption (https://github.com/xqq/libaribcaption/blob/master/CMakeLists.txt)
 - [ ] vapoursynth (R65/R63)


## The libraries below are available in vcpkg, need testing whether their versions are compatible with libmpv.

 - [x] ANGLE
 - [x] FFmpeg
 - [x] x264
 - [x] x265
 - [x] uchardet
 - [x] rubberband (with libsamplerate)
 - [x] opus
 - [x] openal-soft
 - [x] luajit
 - [x] libvpx
 - [x] libwebp
 - [x] libpng
 - [x] libunibreak
 - [x] libass
 - [x] lcms2
 - [x] lame
 - [x] harfbuzz
 - [x] freetype2
 - [x] flac
 - [x] opus-tools
 - [x] mujs
 - [x] libarchive
 - [x] shaderc (with spirv-headers, spirv-tools, glslang)
 - [x] vulkan-header
 - [x] vulkan
 - [x] spirv-cross
 - [x] fribidi
 - [x] nettle
 - [x] curl
 - [x] libxml2
 - [x] amf-headers
 - [x] nvcodec-headers
 - [x] megasdk (with readline, cryptopp, sqlite, libuv, libsodium)
 - [x] aom
 - [x] dav1d
 - [x] libplacebo (with glad, fast_float, xxhash)
 - [x] fontconfig
 - [x] libssh
 - [x] libsrt
 - [x] libjxl (with brotli, highway)
 - [x] libmodplug
 - [x] zlib (zlib-ng)
 - [x] zstd
 - [x] expat
 - [x] openssl
 - [x] libsdl2
 - [x] speex
 - [x] vorbis

