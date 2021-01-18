OPTS+="-DCMAKE_BUILD_TYPE=Release \
       -DCMAKE_SKIP_RPATH=ON \
       -DUSE_SYSTEM_LIBZIP=ON \
       -DUSE_SYSTEM_SNAPPY=ON"

default_cmake_build &&
default_make &&
prepare_install &&

install -m 755 $SOURCE_DIRECTORY/ppsspp-oosb/PPSSPPSDL -t /usr/bin &&
cp -dr --no-preserve=ownership $SOURCE_DIRECTORY/icons/hicolor /usr/share/icons/ &&
mkdir -p /usr/share/ppsspp &&
cp -dr --no-preserve=ownership $SOURCE_DIRECTORY/ppsspp-oosb/assets /usr/share/ppsspp/ &&
cp $SOURCE_DIRECTORY/icons/icon-512.svg /usr/share/pixmaps/ppsspp.svg &&
install -m 755 $SCRIPT_DIRECTORY/ppsspp.desktop -t /usr/share/applications/
