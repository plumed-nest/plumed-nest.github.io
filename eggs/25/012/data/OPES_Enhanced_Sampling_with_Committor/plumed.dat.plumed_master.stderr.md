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
[runnervmw9dnm:05628] *** Process received signal ***
[runnervmw9dnm:05628] Signal: Aborted (6)
[runnervmw9dnm:05628] Signal code:  (-6)
[runnervmw9dnm:05628] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f661b045330]
[runnervmw9dnm:05628] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f661b09eb2c]
[runnervmw9dnm:05628] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f661b04527e]
[runnervmw9dnm:05628] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f661b0288ff]
[runnervmw9dnm:05628] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f661b4a5ff5]
[runnervmw9dnm:05628] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f661b4bb0da]
[runnervmw9dnm:05628] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f661b4a5a55]
[runnervmw9dnm:05628] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f661b4a5a6f]
[runnervmw9dnm:05628] [ 8] plumed_master(+0x146dd)[0x557bf48026dd]
[runnervmw9dnm:05628] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f661b02a1ca]
[runnervmw9dnm:05628] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f661b02a28b]
[runnervmw9dnm:05628] [11] plumed_master(+0x15365)[0x557bf4803365]
[runnervmw9dnm:05628] *** End of error message ***
</pre>
{% endraw %}
