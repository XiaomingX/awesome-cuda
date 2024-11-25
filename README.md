# awesome-CUDA ( CUDA 学习资源精选 )

### 讲座和演讲资料

- [CUDA C/C++ 基础](https://www.olcf.ornl.gov/wp-content/uploads/2013/02/Intro_to_CUDA_C-TS.pdf)  
  介绍 CUDA 核函数、内存管理、线程与线程块、共享内存及线程同步。包含基础示例如加法核函数及优化的 1D 模板核函数。

- [CUDA 高级优化 - 提高 20 倍性能](https://www.nvidia.com/content/cudazone/download/Advanced_CUDA_Training_NVISION08.pdf)  
  涵盖 Tesla 10 系列架构、主机到设备的内存传输、异步数据传输、共享内存及共存访问优化等高级话题。

- [CUDA 内存优化](http://on-demand.gputechconf.com/gtc-express/2011/presentations/NVIDIA_GPU_Computing_Webinars_CUDA_Memory_Optimization.pdf)  
  讲解异步数据传输、零拷贝、内存带宽优化、共享内存冲突以及矩阵转置示例。

- [低占用率下的更高性能](http://www.nvidia.com/content/GTC-2010/pdfs/2238_GTC2010.pdf)  
  探讨通过指令级并行和线程级并行提高性能的技巧，示例包括矩阵乘法优化。

### 库

- [Thrust](https://github.com/thrust/thrust)  
  一个简化并行编程的高效算法库，适合快速开发。如果需要更高性能，可考虑使用更底层的库如 CUDPP。

- [CUDPP](https://github.com/cudpp/cudpp)  
  提供多种并行计算原语（如前缀和、流压缩），适用于需要高性能优化的应用。

- [Modern GPU](https://nvlabs.github.io/moderngpu/index.html)  
  包含 CUDA 算法和性能优化策略的详解，以及相应的代码实现。

### 论文和研究

- [高效并行扫描算法](http://www.idav.ucdavis.edu/publications/print_pub?pub_id=1041)  
  使用分治法高效实现扫描和分段扫描算法的详细介绍。

- [高效流压缩在宽 SIMD 架构上的实现](http://www.cse.chalmers.se/~uffe/streamcompaction.pdf)  
  流压缩算法的详细描述，CUDPP 库即基于此研究。

- [CUDA 直方图计算](http://developer.download.nvidia.com/compute/cuda/1.1-Beta/x86_website/projects/histogram64/doc/histogram.pdf)  
  详细讲解如何在 CUDA 中计算直方图。

### 实用文章

- [CUDA 快速直方图计算](https://devblogs.nvidia.com/parallelforall/gpu-pro-tip-fast-histograms-using-shared-atomics-maxwell/)  
  使用共享内存和原子操作加速直方图计算。

- [CUDA 快速并行归约优化](https://devblogs.nvidia.com/parallelforall/faster-parallel-reductions-kepler/)  
  提供在 Kepler 架构上进一步优化归约算法的技巧。

### 视频教程

- [并行编程入门 - CUDA](https://www.youtube.com/playlist?list=PLGvfHSgImk4aweyWlhBXNF6XISY3um82_)  
  Udacity 出品的 CUDA 基础教程，适合初学者入门。
