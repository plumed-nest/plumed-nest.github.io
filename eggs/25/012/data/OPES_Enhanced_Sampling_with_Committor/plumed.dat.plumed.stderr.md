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
[pkrvmbietmlfzoi:62311] *** Process received signal ***
[pkrvmbietmlfzoi:62311] Signal: Aborted (6)
[pkrvmbietmlfzoi:62311] Signal code:  (-6)
[pkrvmbietmlfzoi:62311] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc796645330]
[pkrvmbietmlfzoi:62311] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc79669eb2c]
[pkrvmbietmlfzoi:62311] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc79664527e]
[pkrvmbietmlfzoi:62311] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7966288ff]
[pkrvmbietmlfzoi:62311] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc796aa5ff5]
[pkrvmbietmlfzoi:62311] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc796abb0da]
[pkrvmbietmlfzoi:62311] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc796aa5a55]
[pkrvmbietmlfzoi:62311] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc796aa5a6f]
[pkrvmbietmlfzoi:62311] [ 8] plumed(+0x146dd)[0x55662c5fa6dd]
[pkrvmbietmlfzoi:62311] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc79662a1ca]
[pkrvmbietmlfzoi:62311] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc79662a28b]
[pkrvmbietmlfzoi:62311] [11] plumed(+0x15365)[0x55662c5fb365]
[pkrvmbietmlfzoi:62311] *** End of error message ***
</pre>
{% endraw %}
