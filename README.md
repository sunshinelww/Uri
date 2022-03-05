# 项目介绍
使用c++写WebServer

# 编译运行
依赖在main.xml里面

# 初始化项目
git clone git@github.com:rhymu8354/Uri.git
cd Uri
git checkout 5e69673563dd72f23dabc1f6d86ad684710b23bb
cd ..
git clone https://github.com/google/googletest.git
cd googletest
git checkout a18ac392d883ca88d1849b90071cea5608fd9293

# 使用cmake构建xcode项目
mkdir build
cd build
cmake3 -G "xcode" ..
cmake --build . --config Debug