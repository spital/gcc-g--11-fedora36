
# Build gcc/g++ v 11.3.0 in Fedora 36

for use with NVIDIA CUDA SDK / nvcc

``` bash
bash ./build.gcc.11.3.sh
source ~/opt/gcc-11.3.0/activate
gcc --version  # 11.3.0 expected
g++ --version  # 11.3.0 expected
```

If problems, mayby better to use `gcc-11.3.1-4.fc35.src.rpm` from Fedora koji.
