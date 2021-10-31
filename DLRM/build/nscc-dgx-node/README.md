# Building the DLRM (Native) on NSCC

## Task
  1. To build the Pytorch with Torch-UCC (build unsuccessful)

## DGX-Node Envorionment
  - CUDA 10.1 (/home/app/cuda10.1)


## Step to build
  0. 
    .
    └── DLRM
        ├── .src.dgx
        │    ├── install_1_gcc7.3.pbs​
        │    ├── install_2_openssl.pbs​
        │    ├── install_2-1_libffi3.2.1.pbs​
        │    ├── install_3_python3.8.pbs​
        │    ├── install_4_ucx.pbs​
        │    ├── install_5_ucc.pbs​
        │    ├── install_6_ompi.pbs​
        │    ├── install_7_pytorch.pbs​
        │    └── install_8_torch-ucc.pbs
        └── .local.dgx
             ├── gcc-7.3​
             ├── libffi3.2.1​
             ├── ompi​
             ├── openssl​
             ├── python​
             ├── torch-ucc​
             ├── ucx​
             └── ucc

  1. To clone and download dependencies.

    git clone ....

  2. 