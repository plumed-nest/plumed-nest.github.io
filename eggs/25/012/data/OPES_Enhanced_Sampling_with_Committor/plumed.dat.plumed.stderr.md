**Project ID:** [plumID:25.012]({{ '/' | absolute_url }}eggs/25/012/)  
Stderr for source:  OPES_Enhanced_Sampling_with_Committor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ./pytorch_model_bias.so
libxpmem.so.0: cannot open shared object file: No such file or directory
[runnervmvrwv9:04740] *** Process received signal ***
[runnervmvrwv9:04740] Signal: Aborted (6)
[runnervmvrwv9:04740] Signal code:  (-6)
[runnervmvrwv9:04740] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f05d9445330]
[runnervmvrwv9:04740] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f05d949eb2c]
[runnervmvrwv9:04740] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f05d944527e]
[runnervmvrwv9:04740] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05d94288ff]
[runnervmvrwv9:04740] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f05d98a5ff5]
[runnervmvrwv9:04740] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f05d98bb0da]
[runnervmvrwv9:04740] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f05d98a5a55]
[runnervmvrwv9:04740] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f05d98a5a6f]
[runnervmvrwv9:04740] [ 8] plumed(+0x146dd)[0x555ee7c976dd]
[runnervmvrwv9:04740] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f05d942a1ca]
[runnervmvrwv9:04740] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f05d942a28b]
[runnervmvrwv9:04740] [11] plumed(+0x15365)[0x555ee7c98365]
[runnervmvrwv9:04740] *** End of error message ***
</pre>
{% endraw %}
