sudo apt install clang cmake libclang-dev llvm-dev rapidjson-dev
git clone --depth=1 --recursive https://github.com/MaskRay/ccls
cmake -H. -BRelease
cmake --build Release

than move ccls from Realse to /usr/bin

