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
[runnervm76f27:05508] *** Process received signal ***
[runnervm76f27:05508] Signal: Aborted (6)
[runnervm76f27:05508] Signal code:  (-6)
[runnervm76f27:05508] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe1dd045330]
[runnervm76f27:05508] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe1dd09ec0c]
[runnervm76f27:05508] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe1dd04527e]
[runnervm76f27:05508] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe1dd0288ff]
[runnervm76f27:05508] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe1dd4a5ff5]
[runnervm76f27:05508] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe1dd4bb0da]
[runnervm76f27:05508] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe1dd4a5a55]
[runnervm76f27:05508] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe1dd4a5a6f]
[runnervm76f27:05508] [ 8] plumed_master(+0x146dd)[0x55a64b9706dd]
[runnervm76f27:05508] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe1dd02a1ca]
[runnervm76f27:05508] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe1dd02a28b]
[runnervm76f27:05508] [11] plumed_master(+0x15365)[0x55a64b971365]
[runnervm76f27:05508] *** End of error message ***
</pre>
{% endraw %}
