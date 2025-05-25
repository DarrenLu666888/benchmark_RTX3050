nvbandwidth Version: v0.8
Built from Git version: v0.8

CUDA Runtime Version: 12080
CUDA Driver Version: 12080
Driver Version: 572.83

darrenlu
Device 0: NVIDIA GeForce RTX 3050 Laptop GPU (00000000:01:00)

Running host_to_device_memcpy_ce.
memcpy CE CPU(row) -> GPU(column) bandwidth (GB/s)
           0
 0     12.98

SUM host_to_device_memcpy_ce 12.98

Running device_to_host_memcpy_ce.
memcpy CE CPU(row) <- GPU(column) bandwidth (GB/s)
           0
 0     13.17

SUM device_to_host_memcpy_ce 13.17

Running host_to_device_bidirectional_memcpy_ce.
memcpy CE CPU(row) <-> GPU(column) bandwidth (GB/s)
           0
 0     12.66

SUM host_to_device_bidirectional_memcpy_ce 12.66

Running device_to_host_bidirectional_memcpy_ce.
memcpy CE CPU(row) <-> GPU(column) bandwidth (GB/s)
           0
 0     11.06

SUM device_to_host_bidirectional_memcpy_ce 11.06

Waived: 
Waived: 
Waived: 
Waived: 
Running all_to_host_memcpy_ce.
memcpy CE CPU(row) <- GPU(column) bandwidth (GB/s)
           0
 0     13.18

SUM all_to_host_memcpy_ce 13.18

Running all_to_host_bidirectional_memcpy_ce.
memcpy CE CPU(row) <-> GPU(column) bandwidth (GB/s)
           0
 0     11.07

SUM all_to_host_bidirectional_memcpy_ce 11.07

Running host_to_all_memcpy_ce.
memcpy CE CPU(row) -> GPU(column) bandwidth (GB/s)
           0
 0     12.96

SUM host_to_all_memcpy_ce 12.96

Running host_to_all_bidirectional_memcpy_ce.
memcpy CE CPU(row) <-> GPU(column) bandwidth (GB/s)
           0
 0     11.39

SUM host_to_all_bidirectional_memcpy_ce 11.39

Waived: 
Waived: 
Waived: 
Waived: 
Running host_to_device_memcpy_sm.
memcpy SM CPU(row) -> GPU(column) bandwidth (GB/s)
           0
 0      9.95

SUM host_to_device_memcpy_sm 9.95

Running device_to_host_memcpy_sm.
memcpy SM CPU(row) <- GPU(column) bandwidth (GB/s)
           0
 0      8.76

SUM device_to_host_memcpy_sm 8.76

Running host_to_device_bidirectional_memcpy_sm.
memcpy SM CPU(row) <-> GPU(column) bandwidth (GB/s)
           0
 0      7.33

SUM host_to_device_bidirectional_memcpy_sm 7.33

Running device_to_host_bidirectional_memcpy_sm.
memcpy SM CPU(row) <-> GPU(column) bandwidth (GB/s)
           0
 0      7.36

SUM device_to_host_bidirectional_memcpy_sm 7.36

Waived: 
Waived: 
Waived: 
Waived: 
Running all_to_host_memcpy_sm.
memcpy SM CPU(row) <- GPU(column) bandwidth (GB/s)
           0
 0      8.79

SUM all_to_host_memcpy_sm 8.79

Running all_to_host_bidirectional_memcpy_sm.
memcpy SM CPU(row) <-> GPU(column) bandwidth (GB/s)
           0
 0      7.40

SUM all_to_host_bidirectional_memcpy_sm 7.40

Running host_to_all_memcpy_sm.
memcpy SM CPU(row) -> GPU(column) bandwidth (GB/s)
           0
 0      9.95

SUM host_to_all_memcpy_sm 9.95

Running host_to_all_bidirectional_memcpy_sm.
memcpy SM CPU(row) <-> GPU(column) bandwidth (GB/s)
           0
 0      7.39

SUM host_to_all_bidirectional_memcpy_sm 7.39

Waived: 
Waived: 
Waived: 
Waived: 
Running host_device_latency_sm.
memory latency SM CPU(row) <-> GPU(column) (ns)
           0
 0    613.22

SUM host_device_latency_sm 613.22

Waived: 
Running device_local_copy.
memcpy local GPU(column) bandwidth (GB/s)
           0
 0     84.33

SUM device_local_copy 84.33

NOTE: The reported results may not reflect the full capabilities of the platform.
Performance can vary with software drivers, hardware clocks, and system topology.