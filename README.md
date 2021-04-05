# vortex-toolchain-prebuilt

To extract the prebuilt files, first we need to extract them:
## llvm-riscv
      Step 1:
      cat llvm-riscv* > llvm-riscv.tar.gz
      Step 2:
      tar -xvf llvm-riscv.tar.gz -C /opt/

## pocl
      Step 1:
      sudo tar -xvf pocl.tar.bz2 -C /opt/
      
## verilator 
      Step 1:
      sudo tar -xvf verilator.tar.bz2 -C /opt/
