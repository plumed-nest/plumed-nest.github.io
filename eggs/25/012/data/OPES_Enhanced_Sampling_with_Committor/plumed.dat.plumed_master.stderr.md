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
[pkrvmbietmlfzoi:62326] *** Process received signal ***
[pkrvmbietmlfzoi:62326] Signal: Aborted (6)
[pkrvmbietmlfzoi:62326] Signal code:  (-6)
[pkrvmbietmlfzoi:62326] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f64bf845330]
[pkrvmbietmlfzoi:62326] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f64bf89eb2c]
[pkrvmbietmlfzoi:62326] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f64bf84527e]
[pkrvmbietmlfzoi:62326] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f64bf8288ff]
[pkrvmbietmlfzoi:62326] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64bfca5ff5]
[pkrvmbietmlfzoi:62326] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64bfcbb0da]
[pkrvmbietmlfzoi:62326] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64bfca5a55]
[pkrvmbietmlfzoi:62326] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64bfca5a6f]
[pkrvmbietmlfzoi:62326] [ 8] plumed_master(+0x146dd)[0x55eb0e8116dd]
[pkrvmbietmlfzoi:62326] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f64bf82a1ca]
[pkrvmbietmlfzoi:62326] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f64bf82a28b]
[pkrvmbietmlfzoi:62326] [11] plumed_master(+0x15365)[0x55eb0e812365]
[pkrvmbietmlfzoi:62326] *** End of error message ***
</pre>
{% endraw %}
