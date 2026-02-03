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
[runnervmkj6or:04378] *** Process received signal ***
[runnervmkj6or:04378] Signal: Aborted (6)
[runnervmkj6or:04378] Signal code:  (-6)
[runnervmkj6or:04378] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc4c0045330]
[runnervmkj6or:04378] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc4c009eb2c]
[runnervmkj6or:04378] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc4c004527e]
[runnervmkj6or:04378] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4c00288ff]
[runnervmkj6or:04378] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4c04a5ff5]
[runnervmkj6or:04378] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4c04bb0da]
[runnervmkj6or:04378] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4c04a5a55]
[runnervmkj6or:04378] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4c04a5a6f]
[runnervmkj6or:04378] [ 8] plumed_master(+0x146dd)[0x5592cab5a6dd]
[runnervmkj6or:04378] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc4c002a1ca]
[runnervmkj6or:04378] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc4c002a28b]
[runnervmkj6or:04378] [11] plumed_master(+0x15365)[0x5592cab5b365]
[runnervmkj6or:04378] *** End of error message ***
</pre>
{% endraw %}
