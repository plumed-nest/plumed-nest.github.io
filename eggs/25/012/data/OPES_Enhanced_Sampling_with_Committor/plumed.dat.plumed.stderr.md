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
[pkrvmq0rgcvqdmg:06165] *** Process received signal ***
[pkrvmq0rgcvqdmg:06165] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06165] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06165] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f436e245330]
[pkrvmq0rgcvqdmg:06165] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f436e29eb2c]
[pkrvmq0rgcvqdmg:06165] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f436e24527e]
[pkrvmq0rgcvqdmg:06165] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f436e2288ff]
[pkrvmq0rgcvqdmg:06165] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f436e6a5ff5]
[pkrvmq0rgcvqdmg:06165] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f436e6bb0da]
[pkrvmq0rgcvqdmg:06165] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f436e6a5a55]
[pkrvmq0rgcvqdmg:06165] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f436e6a5a6f]
[pkrvmq0rgcvqdmg:06165] [ 8] plumed(+0x146dd)[0x5604f9f896dd]
[pkrvmq0rgcvqdmg:06165] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f436e22a1ca]
[pkrvmq0rgcvqdmg:06165] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f436e22a28b]
[pkrvmq0rgcvqdmg:06165] [11] plumed(+0x15365)[0x5604f9f8a365]
[pkrvmq0rgcvqdmg:06165] *** End of error message ***
</pre>
{% endraw %}
