pkg_add jack
pkg_add ruby
pkg_add cmake
pkg_add libsndfile
pkg_add fftw
pkg_add qt5
pkg_add qtwebengine
cmake -DQt5_DIR=/usr/local/lib/qt5/cmake/Qt5/ -DSC_HIDAPI=OFF -DSC_ABLETON_LINK=OFF ..

