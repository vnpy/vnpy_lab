# vn.py lab

* cpp_api_binding: 
  * 基于clang的C++ API结构分析
  * 自动生成pybind11的封装代码
  * 采用对象（而非字典）作为API中使用的数据结构
  * 使用全局Dispatcher实现Python内的异步回调，只有一个线程从而实现更好的性能（减少GIL获取开销）



