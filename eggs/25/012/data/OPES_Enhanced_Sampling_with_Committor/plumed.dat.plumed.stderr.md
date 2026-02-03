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
[runnervmkj6or:04363] *** Process received signal ***
[runnervmkj6or:04363] Signal: Aborted (6)
[runnervmkj6or:04363] Signal code:  (-6)
[runnervmkj6or:04363] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0a3e445330]
[runnervmkj6or:04363] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0a3e49eb2c]
[runnervmkj6or:04363] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0a3e44527e]
[runnervmkj6or:04363] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0a3e4288ff]
[runnervmkj6or:04363] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0a3e8a5ff5]
[runnervmkj6or:04363] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0a3e8bb0da]
[runnervmkj6or:04363] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0a3e8a5a55]
[runnervmkj6or:04363] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0a3e8a5a6f]
[runnervmkj6or:04363] [ 8] plumed(+0x146dd)[0x55c20ec266dd]
[runnervmkj6or:04363] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0a3e42a1ca]
[runnervmkj6or:04363] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0a3e42a28b]
[runnervmkj6or:04363] [11] plumed(+0x15365)[0x55c20ec27365]
[runnervmkj6or:04363] *** End of error message ***
</pre>
{% endraw %}
