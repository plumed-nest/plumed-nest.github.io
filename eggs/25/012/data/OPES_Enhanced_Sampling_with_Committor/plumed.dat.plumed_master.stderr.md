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
[pkrvm7jw40e0xgp:05652] *** Process received signal ***
[pkrvm7jw40e0xgp:05652] Signal: Aborted (6)
[pkrvm7jw40e0xgp:05652] Signal code:  (-6)
[pkrvm7jw40e0xgp:05652] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd20a445330]
[pkrvm7jw40e0xgp:05652] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd20a49eb2c]
[pkrvm7jw40e0xgp:05652] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd20a44527e]
[pkrvm7jw40e0xgp:05652] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd20a4288ff]
[pkrvm7jw40e0xgp:05652] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd20a8a5ff5]
[pkrvm7jw40e0xgp:05652] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd20a8bb0da]
[pkrvm7jw40e0xgp:05652] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd20a8a5a55]
[pkrvm7jw40e0xgp:05652] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd20a8a5a6f]
[pkrvm7jw40e0xgp:05652] [ 8] plumed_master(+0x146dd)[0x55c63e4c26dd]
[pkrvm7jw40e0xgp:05652] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd20a42a1ca]
[pkrvm7jw40e0xgp:05652] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd20a42a28b]
[pkrvm7jw40e0xgp:05652] [11] plumed_master(+0x15365)[0x55c63e4c3365]
[pkrvm7jw40e0xgp:05652] *** End of error message ***
</pre>
{% endraw %}
