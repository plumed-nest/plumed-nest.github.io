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
[runnervmvrwv9:04761] *** Process received signal ***
[runnervmvrwv9:04761] Signal: Aborted (6)
[runnervmvrwv9:04761] Signal code:  (-6)
[runnervmvrwv9:04761] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3617045330]
[runnervmvrwv9:04761] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f361709eb2c]
[runnervmvrwv9:04761] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f361704527e]
[runnervmvrwv9:04761] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36170288ff]
[runnervmvrwv9:04761] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f36174a5ff5]
[runnervmvrwv9:04761] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f36174bb0da]
[runnervmvrwv9:04761] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f36174a5a55]
[runnervmvrwv9:04761] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f36174a5a6f]
[runnervmvrwv9:04761] [ 8] plumed_master(+0x146dd)[0x55ca6b0f86dd]
[runnervmvrwv9:04761] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f361702a1ca]
[runnervmvrwv9:04761] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f361702a28b]
[runnervmvrwv9:04761] [11] plumed_master(+0x15365)[0x55ca6b0f9365]
[runnervmvrwv9:04761] *** End of error message ***
</pre>
{% endraw %}
