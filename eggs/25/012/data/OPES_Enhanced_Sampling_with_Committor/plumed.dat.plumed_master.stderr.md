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
[pkrvmbietmlfzoi:05523] *** Process received signal ***
[pkrvmbietmlfzoi:05523] Signal: Aborted (6)
[pkrvmbietmlfzoi:05523] Signal code:  (-6)
[pkrvmbietmlfzoi:05523] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe28ba45330]
[pkrvmbietmlfzoi:05523] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe28ba9eb2c]
[pkrvmbietmlfzoi:05523] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe28ba4527e]
[pkrvmbietmlfzoi:05523] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe28ba288ff]
[pkrvmbietmlfzoi:05523] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe28bea5ff5]
[pkrvmbietmlfzoi:05523] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe28bebb0da]
[pkrvmbietmlfzoi:05523] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe28bea5a55]
[pkrvmbietmlfzoi:05523] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe28bea5a6f]
[pkrvmbietmlfzoi:05523] [ 8] plumed_master(+0x146dd)[0x55837f4846dd]
[pkrvmbietmlfzoi:05523] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe28ba2a1ca]
[pkrvmbietmlfzoi:05523] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe28ba2a28b]
[pkrvmbietmlfzoi:05523] [11] plumed_master(+0x15365)[0x55837f485365]
[pkrvmbietmlfzoi:05523] *** End of error message ***
</pre>
{% endraw %}
