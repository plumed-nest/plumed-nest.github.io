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
[pkrvmberfyhpb9w:05464] *** Process received signal ***
[pkrvmberfyhpb9w:05464] Signal: Aborted (6)
[pkrvmberfyhpb9w:05464] Signal code:  (-6)
[pkrvmberfyhpb9w:05464] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3561c45330]
[pkrvmberfyhpb9w:05464] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3561c9eb2c]
[pkrvmberfyhpb9w:05464] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3561c4527e]
[pkrvmberfyhpb9w:05464] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3561c288ff]
[pkrvmberfyhpb9w:05464] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f35620a5ff5]
[pkrvmberfyhpb9w:05464] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f35620bb0da]
[pkrvmberfyhpb9w:05464] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f35620a5a55]
[pkrvmberfyhpb9w:05464] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f35620a5a6f]
[pkrvmberfyhpb9w:05464] [ 8] plumed_master(+0x146dd)[0x5594eeeab6dd]
[pkrvmberfyhpb9w:05464] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3561c2a1ca]
[pkrvmberfyhpb9w:05464] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3561c2a28b]
[pkrvmberfyhpb9w:05464] [11] plumed_master(+0x15365)[0x5594eeeac365]
[pkrvmberfyhpb9w:05464] *** End of error message ***
</pre>
{% endraw %}
