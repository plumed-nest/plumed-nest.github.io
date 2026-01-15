**Project ID:** [plumID:25.012]({{ '/' | absolute_url }}eggs/25/012/)  
Stderr for source:  OPES_Enhanced_Sampling_with_Committor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ./pytorch_model_bias.so
libxpmem.so.0: cannot open shared object file: No such file or directory
[runnervmi13qx:32918] *** Process received signal ***
[runnervmi13qx:32918] Signal: Aborted (6)
[runnervmi13qx:32918] Signal code:  (-6)
[runnervmi13qx:32918] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f73fc245330]
[runnervmi13qx:32918] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f73fc29eb2c]
[runnervmi13qx:32918] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f73fc24527e]
[runnervmi13qx:32918] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f73fc2288ff]
[runnervmi13qx:32918] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f73fc6a5ff5]
[runnervmi13qx:32918] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f73fc6bb0da]
[runnervmi13qx:32918] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f73fc6a5a55]
[runnervmi13qx:32918] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f73fc6a5a6f]
[runnervmi13qx:32918] [ 8] plumed(+0x146dd)[0x561e71cea6dd]
[runnervmi13qx:32918] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f73fc22a1ca]
[runnervmi13qx:32918] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f73fc22a28b]
[runnervmi13qx:32918] [11] plumed(+0x15365)[0x561e71ceb365]
[runnervmi13qx:32918] *** End of error message ***
</pre>
{% endraw %}
