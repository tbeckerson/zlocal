cd $SOURCE_DIRECTORY &&
prepare_install &&
make -f Makefile &&
install -Dm755 $SOURCE_DIRECTORY/$MODULE /usr/bin/$MODULE &&
install -Dm644 $SCRIPT_DIRECTORY/${MODULE}.desktop /usr/share/applications/${MODULE}.desktop
install -Dm644 $SCRIPT_DIRECTORY/${MODULE}.png /usr/share/pixmaps/${MODULE}.png
