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
[pkrvmpptgkbjq6m:06089] *** Process received signal ***
[pkrvmpptgkbjq6m:06089] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06089] Signal code:  (-6)
[pkrvmpptgkbjq6m:06089] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d18645330]
[pkrvmpptgkbjq6m:06089] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d1869eb2c]
[pkrvmpptgkbjq6m:06089] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d1864527e]
[pkrvmpptgkbjq6m:06089] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d186288ff]
[pkrvmpptgkbjq6m:06089] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d18aa5ff5]
[pkrvmpptgkbjq6m:06089] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d18abb0da]
[pkrvmpptgkbjq6m:06089] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d18aa5a55]
[pkrvmpptgkbjq6m:06089] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d18aa5a6f]
[pkrvmpptgkbjq6m:06089] [ 8] plumed(+0x146dd)[0x55625b9ac6dd]
[pkrvmpptgkbjq6m:06089] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d1862a1ca]
[pkrvmpptgkbjq6m:06089] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d1862a28b]
[pkrvmpptgkbjq6m:06089] [11] plumed(+0x15365)[0x55625b9ad365]
[pkrvmpptgkbjq6m:06089] *** End of error message ***
</pre>
{% endraw %}
