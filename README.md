# benchmark_RTX3050
本代码库用来对个人笔记本电脑低端显卡GeForce RTX 3050 4GB的
dram_bandwidth
dram_latency
l2cache_bandwidth
l2cache_latency
l1cache_latency
smem_latency
...(待补充)...
进行测试，争取达到精准，以提高对硬件更深的理解

chatgpt指导意见链接：https://chatgpt.com/share/680e37af-35c0-8012-b10d-58c6d6d809f1

相关spec：https://www.techpowerup.com/gpu-specs/geforce-rtx-3050-4-gb.c3744

## dram_bandwidth
这里的dram其实也就是vram，即显存，带宽的定义如下（from 《CUDA C 编程权威指南》）：
1. 有效带宽（GB/s）=（读字节数+写字节数）*1e-9/运行时间
2. 理论带宽：当前硬件可以实现的绝对最大带宽

我的笔记本RTX3050的显存大小是4GB，从上述spec链接可以看到相关信息是：
```
Memory Size 4 GB
Memory Type GDDR6
Memory Bus 128 bit
Bandwidth 192.0 GB/s
```
测试带宽采用cuda-samples里提供的程序：https://github.com/NVIDIA/cuda-samples/tree/master/Samples/1_Utilities/bandwidthTest

运行结果如下：
```
[CUDA Bandwidth Test] - Starting...
Running on...

 Device 0: NVIDIA GeForce RTX 3050 Laptop GPU
 Quick Mode

 Host to Device Bandwidth, 1 Device(s)
 PINNED Memory Transfers
   Transfer Size (Bytes)        Bandwidth(GB/s)
   32000000                     13.0

 Device to Host Bandwidth, 1 Device(s)
 PINNED Memory Transfers
   Transfer Size (Bytes)        Bandwidth(GB/s)
   32000000                     13.2

 Device to Device Bandwidth, 1 Device(s)
 PINNED Memory Transfers
   Transfer Size (Bytes)        Bandwidth(GB/s)
   32000000                     181.4

Result = PASS

NOTE: The CUDA Samples are not meant for performance measurements. Results may vary when GPU Boost is enabled.
```
