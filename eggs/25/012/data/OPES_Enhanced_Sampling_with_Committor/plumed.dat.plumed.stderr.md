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
[runnervmw9dnm:05613] *** Process received signal ***
[runnervmw9dnm:05613] Signal: Aborted (6)
[runnervmw9dnm:05613] Signal code:  (-6)
[runnervmw9dnm:05613] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f07045330]
[runnervmw9dnm:05613] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f0709eb2c]
[runnervmw9dnm:05613] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f0704527e]
[runnervmw9dnm:05613] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f070288ff]
[runnervmw9dnm:05613] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f074a5ff5]
[runnervmw9dnm:05613] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f074bb0da]
[runnervmw9dnm:05613] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f074a5a55]
[runnervmw9dnm:05613] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f074a5a6f]
[runnervmw9dnm:05613] [ 8] plumed(+0x146dd)[0x55d417dde6dd]
[runnervmw9dnm:05613] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f0702a1ca]
[runnervmw9dnm:05613] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f0702a28b]
[runnervmw9dnm:05613] [11] plumed(+0x15365)[0x55d417ddf365]
[runnervmw9dnm:05613] *** End of error message ***
</pre>
{% endraw %}
