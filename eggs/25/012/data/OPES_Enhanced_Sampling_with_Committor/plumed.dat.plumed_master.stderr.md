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
[pkrvmpptgkbjq6m:06104] *** Process received signal ***
[pkrvmpptgkbjq6m:06104] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06104] Signal code:  (-6)
[pkrvmpptgkbjq6m:06104] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffaeaa45330]
[pkrvmpptgkbjq6m:06104] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffaeaa9eb2c]
[pkrvmpptgkbjq6m:06104] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffaeaa4527e]
[pkrvmpptgkbjq6m:06104] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffaeaa288ff]
[pkrvmpptgkbjq6m:06104] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffaeaea5ff5]
[pkrvmpptgkbjq6m:06104] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffaeaebb0da]
[pkrvmpptgkbjq6m:06104] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffaeaea5a55]
[pkrvmpptgkbjq6m:06104] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffaeaea5a6f]
[pkrvmpptgkbjq6m:06104] [ 8] plumed_master(+0x146dd)[0x5585546576dd]
[pkrvmpptgkbjq6m:06104] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffaeaa2a1ca]
[pkrvmpptgkbjq6m:06104] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffaeaa2a28b]
[pkrvmpptgkbjq6m:06104] [11] plumed_master(+0x15365)[0x558554658365]
[pkrvmpptgkbjq6m:06104] *** End of error message ***
</pre>
{% endraw %}
