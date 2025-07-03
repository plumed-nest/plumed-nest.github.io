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
[pkrvmbietmlfzoi:05508] *** Process received signal ***
[pkrvmbietmlfzoi:05508] Signal: Aborted (6)
[pkrvmbietmlfzoi:05508] Signal code:  (-6)
[pkrvmbietmlfzoi:05508] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff739845330]
[pkrvmbietmlfzoi:05508] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff73989eb2c]
[pkrvmbietmlfzoi:05508] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff73984527e]
[pkrvmbietmlfzoi:05508] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff7398288ff]
[pkrvmbietmlfzoi:05508] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff739ca5ff5]
[pkrvmbietmlfzoi:05508] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff739cbb0da]
[pkrvmbietmlfzoi:05508] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff739ca5a55]
[pkrvmbietmlfzoi:05508] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff739ca5a6f]
[pkrvmbietmlfzoi:05508] [ 8] plumed(+0x146dd)[0x55f08a0a46dd]
[pkrvmbietmlfzoi:05508] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff73982a1ca]
[pkrvmbietmlfzoi:05508] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff73982a28b]
[pkrvmbietmlfzoi:05508] [11] plumed(+0x15365)[0x55f08a0a5365]
[pkrvmbietmlfzoi:05508] *** End of error message ***
</pre>
{% endraw %}
