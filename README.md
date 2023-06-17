# 开源库整理

##### 通用框架

| 库名       | 简介                                                         | 地址                                 |
| ---------- | ------------------------------------------------------------ | ------------------------------------ |
| boost      | 这个不解释了...                                              |                                      |
| folly      | facebook的通用库, 定位是作为boost的补充(但是在window下特别难编译...) | https://github.com/facebook/folly    |
| poco       | boost补充,内容侧重于网络(特别是嵌入式网络)                   | https://github.com/pocoproject/poco  |
| abseil-cpp | std标准库扩充                                                | https://github.com/abseil/abseil-cpp |
|            |                                                              |                                      |



##### UI

| 库名      | 简介           | 地址                                   |
| --------- | -------------- | -------------------------------------- |
| imgui     | 开源跨平台UI库 | https://github.com/ocornut/imgui       |
| wxWidgets | 开源跨平台UI库 | https://github.com/wxWidgets/wxWidgets |
|           |                |                                        |



##### 网络

| 库名        | 简介                               | 地址                                      |
| ----------- | ---------------------------------- | ----------------------------------------- |
| grpc        | rpc框架                            | https://github.com/grpc/grpc              |
| brpc        | rpc框架                            | https://github.com/apache/brpc            |
| cpp-httplib | 仅头文件的跨平台HTTP/HTTPS库       | https://github.com/yhirose/cpp-httplib    |
| drogon      | 基于 C++14/17 的 HTTP 应用程序框架 | https://github.com/drogonframework/drogon |
| crow        | 用于 Web 的 C++ 微框架             | https://github.com/ipkn/crow              |
| oatpp       | C++ 的现代 Web 框架                | https://github.com/oatpp/oatpp            |
| hpsocket    | 高性能网络框架                     | https://github.com/ldcsaa/HP-Socket       |
| libzmq      | 轻量级消息传递内核                 | https://github.com/zeromq/libzmq          |
|             |                                    |                                           |



##### 序列化/反序列化相关

| 库名                        | 简介               | 地址                                           |
| --------------------------- | ------------------ | ---------------------------------------------- |
| nlohmann/json               | 接口最友好的json库 | https://github.com/nlohmann/json               |
| open-source-parsers/jsoncpp | json库             | https://github.com/open-source-parsers/jsoncpp |
| ArduinoJson                 | json库             | https://github.com/bblanchon/ArduinoJson       |
| tinyxml2                    | C++ XML 解析器     | https://github.com/leethomason/tinyxml2        |
| pugixml                     | C++ XML 解析器     | https://github.com/zeux/pugixml                |
| yaml-cpp                    | yaml解析器         | https://github.com/jbeder/yaml-cpp             |
|                             |                    |                                                |



##### 单元测试

| 库名    | 简介         | 地址                               |
| ------- | ------------ | ---------------------------------- |
| catch2  | 单元测试框架 | https://github.com/catchorg/Catch2 |
| doctest | C++ 测试框架 | https://github.com/doctest/doctest |
|         |              |                                    |



##### 日志

| 库名   | 简介                    | 地址                             |
| ------ | ----------------------- | -------------------------------- |
| spdlog | 快速日志库(底层依赖fmt) | https://github.com/gabime/spdlog |
| glog   | google的日志库          | https://github.com/google/glog   |
|        |                         |                                  |



##### 算法

| 库名       | 简介                         | 地址                                                  |
| ---------- | ---------------------------- | ----------------------------------------------------- |
| dlib       | 视觉算法库(侧重人脸识别方面) | https://github.com/davisking/dlib                     |
| annoy      | 近似最近邻搜索的C++库        | https://github.com/spotify/annoy                      |
| xgboost    | 分布式的梯度提示框架         | https://github.com/dmlc/xgboost                       |
| Flashlight | C++机器学习库                | https://github.com/flashlight/flashlight              |
| thrust     | 并行算法库                   | https://github.com/NVIDIA/thrust                      |
| CGAL       | 非常强大的几何计算库         | https://github.com/CGAL/cgal                          |
| Eigen      | 这个就不解释了吧...          | https://eigen.tuxfamily.org/index.php?title=Main_Page |
| Ceres      | 大规模的非线性优化库         | https://github.com/ceres-solver/ceres-solver          |
| wykobi     | 2D几何计算库                 | https://www.wykobi.com/                               |
| RansacLib  | RANSAC算法                   | https://github.com/tsattler/RansacLib                 |
|            |                              |                                                       |



##### 解析器/包装器

| 库名     | 简介                                     | 地址                               |
| -------- | ---------------------------------------- | ---------------------------------- |
| swig     | 简化的包装器和接口生成器(导出为脚本语言) | https://github.com/swig/swig       |
| sol2     | 封装到LUA的包装器                        | https://github.com/ThePhD/sol2     |
| pybind11 | C++11 和 Python的绑定(仅头文件好评)      | https://github.com/pybind/pybind11 |
|          |                                          |                                    |



##### 编程补充

| 库名            | 简介                                 | 地址                                          |
| --------------- | ------------------------------------ | --------------------------------------------- |
| ThreadPool      | 简单仅头文件的线程池库(仅头文件好评) | https://github.com/progschj/ThreadPool        |
| re2             | 快速,友好,线程友好的正则表达式库     | https://github.com/google/re2                 |
| concurrentqueue | 用于 C++ 的工业级无锁队列            | https://github.com/cameron314/concurrentqueue |
| magic_enum      | C++枚举反射库                        | https://github.com/Neargye/magic_enum         |
| taskflow        | 任务流                               | https://github.com/taskflow/taskflow          |
| cxxopts         | 轻量级*C* ++ 命令行选项解析器        | https://github.com/jarro2783/cxxopts          |
|                 |                                      |                                               |



##### 其他

| 库名     | 简介                | 地址                                 |
| -------- | ------------------- | ------------------------------------ |
| LibreCAD | 基于qt的CAD绘图工具 | https://github.com/LibreCAD/LibreCAD |
|          |                     |                                      |

