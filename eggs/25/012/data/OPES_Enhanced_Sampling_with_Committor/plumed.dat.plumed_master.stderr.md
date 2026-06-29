**Project ID:** [plumID:25.012]({{ '/' | absolute_url }}eggs/25/012/)  
Stderr for source:  OPES_Enhanced_Sampling_with_Committor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ./pytorch_model_bias.so
libxpmem.so.0: cannot open shared object file: No such file or directory
[runnervmmklqx:04397] *** Process received signal ***
[runnervmmklqx:04397] Signal: Aborted (6)
[runnervmmklqx:04397] Signal code:  (-6)
[runnervmmklqx:04397] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff1a3645330]
[runnervmmklqx:04397] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff1a369eb2c]
[runnervmmklqx:04397] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff1a364527e]
[runnervmmklqx:04397] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1a36288ff]
[runnervmmklqx:04397] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1a3aa5ff5]
[runnervmmklqx:04397] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1a3abb0da]
[runnervmmklqx:04397] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1a3aa5a55]
[runnervmmklqx:04397] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1a3aa5a6f]
[runnervmmklqx:04397] [ 8] plumed_master(+0x146dd)[0x55e1b62b76dd]
[runnervmmklqx:04397] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff1a362a1ca]
[runnervmmklqx:04397] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff1a362a28b]
[runnervmmklqx:04397] [11] plumed_master(+0x15365)[0x55e1b62b8365]
[runnervmmklqx:04397] *** End of error message ***
</pre>
{% endraw %}
