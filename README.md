# MClient-server
MClient-server is another version of Client-Server where a single server can handle multiple client. The library used to achieve this is OpenMP.
# setup
All you need to do is to add `-fopenmp` in compile argument in you IDE
  - <b>For Dev C++</b>
    - For Dev C++ go to `tools>Compile Options` and add the argument mention above in General tab
  - <b> CodeBlocks </b>
    * [CodeBlocks setup](http://instincttechies.blogspot.com/2013/06/how-to-use-openmp-in-codeblocks.html)
# How it works
The port is fixed to 5000, no need to specify it in the arguments anymore. Furthermore, the server gets more realistic now. The reply of the server is now automatique, it replies with `Welcome....`.
