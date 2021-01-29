My Lunar Linux (https://lunar-linux.org) _zlocal_ files. __Use at your own risk, these may not work properly on your system. These could be updated / altered / removed at any time.__

modules with a __*star__ beside the name are new modules, the others are modifications to existing modules. Anything with an __!exclamation__ has a pull request in and will be removed when the changes are merged.

__*Heimer__ - mindmapping tool.

__ImageMagick__ - added libraqm support.

__*MultiMC5__ - Advanced launcher for Minecraft. _Requires a wget of submodules. WIP._

__*OpenSceneGraph__ - 3D Graphics Toolkit. _BROKEN :(_

__*RetroArch__ - Multi game system emulator.

__*Spice-up__ - Presentation maker, part of Elementary OS. Pulls in __*granite.__ as dependency.

__*anything_sync_daemon__ - puts chosen folders into ramdisk on boot, restores them to drive on shutdown.

__*appstream-glib__ - Objects and helpers for AppStream metadata. Required by __*flatpak__ and __*gimp-git.__

__aqbanking__ - Updated to newest version. Required by __*gnucash.__

__!birdtray__ - systemtray notifier for Thunderbird. version bump.

__darktable__ - updated to newest version.

__*discount__ - markdown parsing library. Needed by __Minder.__

__*dolphin-emu-git__ - Nintendo GameCube & Wii emulator. _Uses git-master, might install today but fail tomorrow. Use with extreme caution._

__*flips__ - IPS file patching utility. _Uses git-master, be cautious._

__*fmt__ - text formatting library. Used by _pcsx2-git._

__fontconfig__ - patched to work with xfce4.

__galculator__ - version bump.

__gcr__ - added missing DEPENDS.

__*gimp-devel__ - Powerful raster image editing program. Pulls in __*appstream-glib__ as dependency. _This is the official development release. Use with caution._

__*!gmic-qt__ - Raster image editing program. GUI frontends to the GMIC libraries.

__gnome-keyring__ - added patch for libcap fix.

__*gnucash__ - Home and small-business accounting. Pulls in _aqbanking_ and _gwenhywfar_ as dependencies.

__*google-fonts__ Pulls the _master.zip_ from Github and copies the fonts to /usr/share/fonts.

__*granite__ - Extensions for GTK3, by Elementary OS. Needed for __Minder and Spice-up.__

__gvfs__ - Updated DEPENDS to recent version of _fuse._

__gwenhywfar__ - Updates DETAILS to latest version, and disables gui support. _WIP, use with caution._

__*libclc__ - opencl support in llvm / clang.

__libcloudproviders__ - Updated DEPENDS.

__libdbi-drivers__ - Updated DEPENDS to use generic %MYSQL alias.

__linux__ - version bump.

__llvm__ - added in opencl support. Requires __libclc.__

__mariadb__ - version bump.

__mate-desktop__ - tentative start for the MATE desktop environment.

__*mednafen__ - Command-line multi-system game emulator.

__*mednaffe__ - GTK3 frontend for _mednafen_ (which it pulls as a dependency).

__mesa-lib__ - Added OpenCL support.

__*multiload-ng__ - Graphical system monitor for _any_ panel.

__node__ - fixed DEPENDS to use Python 3.

__npm__ - version bump. _BROKEN_

__ntfs-3g__ - Mount and modify Microsoft NTFS partitons. Updated the DEPENDS to use _fuse-3_.

__*ocl-icd__ - OpenCL Installable Client Driver.

__*pcsx2-git__ - Playstation 2 emulator. _Uses git-master. Be careful!._

__*pdfslicer__ - extract, merge, rotate and reorder pages of PDF documents. _Requires a submodule init / wget of submodules. WIP.__

__php__ - updating everything. _SEEMS_ to work fine.

__*ppsspp__ - Sony PSP emulator. _Requires an extensive wget of submodules. WIP._

__*psi-notify__ - system load monitoring utility.

__python-markdown__ - updated to use recent python-setuptools.

__r8168__ - Imlpicity create directory that wasn't created by _install._

__rtkit__ - updated to meson build system.

__*srain__ - IRC client for GTK3.

__tagtool__ - Updated DEPENDS to use recent _glade._

__texlive__ - made texlive-texmf an optional_depends.

__xar__ - fix compatability with updated OpenSSL.

__xf86-video-amdgpu__ - fixed gcc 10 compatability, and hardening compiler error.

__xfce4-taskmanager__ - removed GTK2 support.

__xfdashboard__ - version bump.

__*xiccd__ - Commandline based colour profile manager.
