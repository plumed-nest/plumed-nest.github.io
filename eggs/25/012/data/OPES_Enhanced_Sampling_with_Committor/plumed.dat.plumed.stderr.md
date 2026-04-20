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
[runnervmeorf1:04170] *** Process received signal ***
[runnervmeorf1:04170] Signal: Aborted (6)
[runnervmeorf1:04170] Signal code:  (-6)
[runnervmeorf1:04170] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe560645330]
[runnervmeorf1:04170] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe56069eb2c]
[runnervmeorf1:04170] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe56064527e]
[runnervmeorf1:04170] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5606288ff]
[runnervmeorf1:04170] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe560aa5ff5]
[runnervmeorf1:04170] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe560abb0da]
[runnervmeorf1:04170] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe560aa5a55]
[runnervmeorf1:04170] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe560aa5a6f]
[runnervmeorf1:04170] [ 8] plumed(+0x146dd)[0x562fd5eaa6dd]
[runnervmeorf1:04170] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe56062a1ca]
[runnervmeorf1:04170] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe56062a28b]
[runnervmeorf1:04170] [11] plumed(+0x15365)[0x562fd5eab365]
[runnervmeorf1:04170] *** End of error message ***
</pre>
{% endraw %}
