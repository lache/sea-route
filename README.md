cmake .. -DPNG_BUILD_ZLIB=true -DZLIB_INCLUDE_DIR=zlib -DZLIB_LIBRARY=zlibstatic -DSKIP_INSTALL_ALL=true

invoke-expression 'cmd /c start powershell -Command {&sea-route.exe --png2rtree c:\sea-server\modis\png-4x2\w1-h0.png --land}'
