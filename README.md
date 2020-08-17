# 3rdPartyLibs
通过如下命令修改安装路径
install_name_tool -id @executable_path/../Frameworks/VEngine.framework/Resources/libpng.x64.dylib /Users/xhnsworks/vengine/lib/x64/libpng.x64.dylib
install_name_tool -id @executable_path/../Frameworks/VEngine.framework/Resources/libfreetype.x64.dylib /Users/xhnsworks/vengine/lib/x64/libfreetype.x64.dylib

install_name_tool -id @executable_path/../Frameworks/VEngine.framework/Resources/libarchive.17.dylib /Users/xhnsworks/vengine/lib/x64/libarchive.17.dylib

通过如下命令查看安装路径
otool -l /Users/xhnsworks/vengine/lib/x64/libpng.x64.dylib

otool -l /Users/xhnsworks/vengine/lib/x64/libarchive.17.dylib
