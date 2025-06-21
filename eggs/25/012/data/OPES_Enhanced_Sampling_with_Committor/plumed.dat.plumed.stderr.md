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
[pkrvmxyh4eaekms:05577] *** Process received signal ***
[pkrvmxyh4eaekms:05577] Signal: Aborted (6)
[pkrvmxyh4eaekms:05577] Signal code:  (-6)
[pkrvmxyh4eaekms:05577] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f68e8245330]
[pkrvmxyh4eaekms:05577] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f68e829eb2c]
[pkrvmxyh4eaekms:05577] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f68e824527e]
[pkrvmxyh4eaekms:05577] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68e82288ff]
[pkrvmxyh4eaekms:05577] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68e86a5ff5]
[pkrvmxyh4eaekms:05577] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68e86bb0da]
[pkrvmxyh4eaekms:05577] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68e86a5a55]
[pkrvmxyh4eaekms:05577] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68e86a5a6f]
[pkrvmxyh4eaekms:05577] [ 8] plumed(+0x146dd)[0x55aa389346dd]
[pkrvmxyh4eaekms:05577] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f68e822a1ca]
[pkrvmxyh4eaekms:05577] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f68e822a28b]
[pkrvmxyh4eaekms:05577] [11] plumed(+0x15365)[0x55aa38935365]
[pkrvmxyh4eaekms:05577] *** End of error message ***
</pre>
{% endraw %}
