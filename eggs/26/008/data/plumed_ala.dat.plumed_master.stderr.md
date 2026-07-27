**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
Stderr for source:  plumed_ala.dat   
Download: [zipped raw stdout](plumed_ala.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_ala.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library OPESmetad.so
OPESmetad.so: cannot open shared object file: No such file or directory
[runnervmvrwv9:04143] *** Process received signal ***
[runnervmvrwv9:04143] Signal: Aborted (6)
[runnervmvrwv9:04143] Signal code:  (-6)
[runnervmvrwv9:04143] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdee8445330]
[runnervmvrwv9:04143] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdee849eb2c]
[runnervmvrwv9:04143] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdee844527e]
[runnervmvrwv9:04143] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdee84288ff]
[runnervmvrwv9:04143] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdee88a5ff5]
[runnervmvrwv9:04143] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdee88bb0da]
[runnervmvrwv9:04143] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdee88a5a55]
[runnervmvrwv9:04143] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdee88a5a6f]
[runnervmvrwv9:04143] [ 8] plumed_master(+0x146dd)[0x5558469ee6dd]
[runnervmvrwv9:04143] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdee842a1ca]
[runnervmvrwv9:04143] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdee842a28b]
[runnervmvrwv9:04143] [11] plumed_master(+0x15365)[0x5558469ef365]
[runnervmvrwv9:04143] *** End of error message ***
</pre>
{% endraw %}
