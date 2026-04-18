# From Infinity GFLOPS to 1D Block Tiling
Today I learned how shared memory works in CUDA...

```cpp
// My fixed kernel code
const uint mathRow = threadIdx.x / BN;
