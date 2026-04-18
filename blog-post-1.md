# From Infinity GFLOPS to 1D Block Tiling
Yesterday I learned how shared memory works in CUDA...

```cpp
// My fixed kernel code
const uint mathRow = threadIdx.x / BN;
// testing this feature
