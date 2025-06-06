# Boost.SmartPtr

This is the CCDC fork of Boost.SmartPtr.

The ccdc_release branch is the main branch containing CCDC modifications to shared_ptr.

This repo is being used to create patch files for our conan boost builds. For example to create a patch to boost-1.88.0 I did

git diff boost-1.88.0 > path.to\boost_ccdc_1_88_0.patch

Then edited that patch file to look more like other patch files
