use_relative_paths = True

# Dependencies on outside packages, as needed for developers/bots that use
# "gclient" instead of raw SVN access.
#
# For now, this must be maintained in parallel with "SVN externals"
# dependencies for developers who use raw SVN instead of "gclient".
# See third_party/externals/README
#
deps = {
  # DEPS using https://chromium.googlesource.com are pulled from chromium @ r205199
  # (see https://chromium.googlesource.com/chromium/chromium/+/c59bfa8ef877f45bfa859669053859857af1d279)
  "third_party/externals/angle" : "https://chromium.googlesource.com/external/angleproject.git@36cced4a9b48cc1e654fbb27477f12fb77b63c91",
  "third_party/externals/freetype" : "https://android.googlesource.com/platform/external/freetype.git@android-4.2.2_r1.2",
  "third_party/externals/gyp" : "https://chromium.googlesource.com/external/gyp.git@8f42386eafcd7ddf1947cab2808a76c315ff30cc",
  "third_party/externals/libjpeg" : "https://chromium.googlesource.com/chromium/deps/libjpeg_turbo.git@82ce8a6d4ebe12a177c0c3597192f2b4f09e81c3",
  "third_party/externals/jsoncpp" : "https://chromium.googlesource.com/external/jsoncpp/jsoncpp.git@ab1e40f3bce061ea6f9bdc60351d6cde2a4f872b",
  "third_party/externals/jsoncpp-chromium" : "https://chromium.googlesource.com/chromium/src/third_party/jsoncpp.git@41239939c0c60481f34887d52c038facf05f5533",
  "third_party/externals/libwebp" : "https://chromium.googlesource.com/webm/libwebp.git@0.3.0",
  "third_party/externals/podofo" : "https://skia.googlesource.com/third_party/podofo.git@skia_ext",
}

deps_os = {
  "android": {
    "platform_tools/android/third_party/externals/expat" : "https://android.googlesource.com/platform/external/expat.git@android-4.2.2_r1.2",
    "platform_tools/android/third_party/externals/gif" : "https://android.googlesource.com/platform/external/giflib.git@android-4.2.2_r1.2",
    "platform_tools/android/third_party/externals/png" : "https://android.googlesource.com/platform/external/libpng.git@android-4.2.2_r1.2",
    "platform_tools/android/third_party/externals/jpeg" : "https://android.googlesource.com/platform/external/jpeg.git@android-4.2.2_r1.2",
  },
  "chromeos": {
    "platform_tools/chromeos/third_party/externals/gif" : "https://android.googlesource.com/platform/external/giflib.git@android-4.2.2_r1.2",
  },
}

#hooks = [
#  {
#    # A change to a .gyp, .gypi, or to GYP itself should run the generator.
#    "pattern": ".",
#    "action": ["python", "trunk/gyp_skia"],
#  },
#]
