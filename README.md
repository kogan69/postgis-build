# postgis-build
```
export CXXFLAGS="-std=c++17"
```
wget https://download.osgeo.org/postgis/source/postgis-3.3.3.tar.gz

tar xvfz postgis-3.3.3.tar.gz

cd postgis-3.3.3/

./autogen.sh

./configure --with-projdir=/opt/homebrew/opt/proj --with-jsondir=/opt/homebrew/opt/json-c   --disable-nls

make

make install
