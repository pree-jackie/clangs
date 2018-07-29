# clangs
where ?


LLVM version 6
export PATH=/home/praveen/ninja/bin:$PATH
clang++ -std=c++17 filename 

LLVM version 7

LLVM is installed using gettingstarted guide in llvm docs.

build command: 

cmake -DCMAKE_BUILD_TYPE=Release -DLLVM_ENABLE_ASSERTIONS=On -DLLVM_PARALLEL_LINK_JOBS=1\

-DLLVM_ENABLE_LLD=1 -DLLVM_TARGETS_TO_BUILD="X86" ../llvm

link command :

cmake --build . -- -j3

make install (which I did after one day)

llvm is installed in /home/praveen/live/install

clang++ - /home/praveen/live/install/bin/clang++

clang   - /home/praveen/live/install/bin/clang

llvm-config - /home/praveen/live/install/bin 

build contains - llvm, clang, lld, compiler-rt, polly, libc++, libc++abi, clang-tools-extra,

To use various projects refer the project documentation.

export PATH=/home/praveen/live/install/bin:$PATH - To include clang, clang++ in search paths.

clang++ -std=c++11,14,17 filename.cpp. 



**Root** 
cd cern_root/root-612-build
source bin/thisroot.sh
root


ssh pvelliengiri@rostam.cct.lsu.edu -p 8000 -i/home/praveen/.ssh/id_rostam
