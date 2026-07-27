**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
Stderr for source:  plumed_chi.dat   
Download: [zipped raw stdout](plumed_chi.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_chi.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ../../plumed_so/OPESmetad.so
../../plumed_so/OPESmetad.so: cannot open shared object file: No such file or directory
[runnervmvrwv9:04249] *** Process received signal ***
[runnervmvrwv9:04249] Signal: Aborted (6)
[runnervmvrwv9:04249] Signal code:  (-6)
[runnervmvrwv9:04249] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0cb0e45330]
[runnervmvrwv9:04249] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0cb0e9eb2c]
[runnervmvrwv9:04249] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0cb0e4527e]
[runnervmvrwv9:04249] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0cb0e288ff]
[runnervmvrwv9:04249] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0cb12a5ff5]
[runnervmvrwv9:04249] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0cb12bb0da]
[runnervmvrwv9:04249] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0cb12a5a55]
[runnervmvrwv9:04249] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0cb12a5a6f]
[runnervmvrwv9:04249] [ 8] plumed_master(+0x146dd)[0x5583ba3056dd]
[runnervmvrwv9:04249] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0cb0e2a1ca]
[runnervmvrwv9:04249] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0cb0e2a28b]
[runnervmvrwv9:04249] [11] plumed_master(+0x15365)[0x5583ba306365]
[runnervmvrwv9:04249] *** End of error message ***
</pre>
{% endraw %}
