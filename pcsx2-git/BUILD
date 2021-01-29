OPTS+=" -DENABLE_TESTS=OFF \
      -DUSE_SYSTEM_YAML=ON \
      -DEXTRA_PLUGINS=ON \
      -DCMAKE_BUILD_TYPE=Release"
      
default_cmake_config &&
default_make &&
prepare_install &&

mkdir -p /usr/share/PCSX2/ &&
cp -r /usr/src/pcsx2-master/bin/plugins /usr/share/PCSX2/ &&
cp -r /usr/src/pcsx2-master/bin/Langs /usr/share/PCSX2/ &&
cp -r /usr/src/pcsx2-master/bin/PCSX2 /usr/bin/ &&
cp -r $SCRIPT_DIRECTORY/pcsx2.desktop /usr/share/applications &&
cp -r $SCRIPT_DIRECTORY/pcsx2.svg /usr/share/pixmaps
