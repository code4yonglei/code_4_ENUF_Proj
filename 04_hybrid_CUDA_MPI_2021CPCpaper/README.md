This repository for the publication ([A hybrid MPI-CUDA approach for nonequispaced discrete Fourier transformation](https://www.sciencedirect.com/science/article/abs/pii/S0010465520302393)) includes two parts: the source code and the input data for the validation of the proposed computational scheme.

## Source code
- ``cunfft.cu`` is used to transfer input data from host (CPU) to device (GPU), compute NDFT in device, and thereafter fetch computational results from device to host. `cunfft.h` is the relelatd head file.
- `util.c` and `util.h` are used for the benchmark.

- `Makefile` contains commands for the hybrid CUDA-MPI compilation scheme, and an executable file named `CUDA_MPI_TEST` will be available after the correct compilation. 






