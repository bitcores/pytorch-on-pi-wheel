# pytorch-on-pi-wheel
Wheel file for pytorch built on an Orange Pi PC, Allwinner H6 chipset, with python3.5 using the following export flags

    export NO_CUDA=1
    export NO_DISTRIBUTED=1    
    export NO_MKLDNN=1     
    export NO_NNPACK=0    
    export NO_QNNPACK=0
    
The Allwinner H3 (and maybe H2+) support NNPACK and QNNPACK (NEON), but other SBCs may not.

You need to install libopenblas-dev at least to use pytorch, install it through the package manager
