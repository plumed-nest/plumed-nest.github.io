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
[runnervmeorf1:04186] *** Process received signal ***
[runnervmeorf1:04186] Signal: Aborted (6)
[runnervmeorf1:04186] Signal code:  (-6)
[runnervmeorf1:04186] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f071fe45330]
[runnervmeorf1:04186] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f071fe9eb2c]
[runnervmeorf1:04186] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f071fe4527e]
[runnervmeorf1:04186] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f071fe288ff]
[runnervmeorf1:04186] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07202a5ff5]
[runnervmeorf1:04186] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07202bb0da]
[runnervmeorf1:04186] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07202a5a55]
[runnervmeorf1:04186] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07202a5a6f]
[runnervmeorf1:04186] [ 8] plumed_master(+0x146dd)[0x55ae9742c6dd]
[runnervmeorf1:04186] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f071fe2a1ca]
[runnervmeorf1:04186] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f071fe2a28b]
[runnervmeorf1:04186] [11] plumed_master(+0x15365)[0x55ae9742d365]
[runnervmeorf1:04186] *** End of error message ***
</pre>
{% endraw %}
