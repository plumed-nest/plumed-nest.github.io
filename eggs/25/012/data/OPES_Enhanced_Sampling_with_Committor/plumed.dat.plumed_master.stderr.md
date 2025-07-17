**Project ID:** [plumID:25.012]({{ '/' | absolute_url }}eggs/25/012/)  
Stderr for source:  OPES_Enhanced_Sampling_with_Committor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ./pytorch_model_bias.so
libxpmem.so.0: cannot open shared object file: No such file or directory
[pkrvmq0rgcvqdmg:06182] *** Process received signal ***
[pkrvmq0rgcvqdmg:06182] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06182] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06182] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2aa4c45330]
[pkrvmq0rgcvqdmg:06182] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2aa4c9eb2c]
[pkrvmq0rgcvqdmg:06182] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2aa4c4527e]
[pkrvmq0rgcvqdmg:06182] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2aa4c288ff]
[pkrvmq0rgcvqdmg:06182] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2aa50a5ff5]
[pkrvmq0rgcvqdmg:06182] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2aa50bb0da]
[pkrvmq0rgcvqdmg:06182] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2aa50a5a55]
[pkrvmq0rgcvqdmg:06182] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2aa50a5a6f]
[pkrvmq0rgcvqdmg:06182] [ 8] plumed_master(+0x146dd)[0x55a74f2056dd]
[pkrvmq0rgcvqdmg:06182] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2aa4c2a1ca]
[pkrvmq0rgcvqdmg:06182] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2aa4c2a28b]
[pkrvmq0rgcvqdmg:06182] [11] plumed_master(+0x15365)[0x55a74f206365]
[pkrvmq0rgcvqdmg:06182] *** End of error message ***
</pre>
{% endraw %}
