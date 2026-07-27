**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
Stderr for source:  plumed_trp.dat   
Download: [zipped raw stdout](plumed_trp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_trp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ../../plumed_so/OPESmetad.so
../../plumed_so/OPESmetad.so: cannot open shared object file: No such file or directory
[runnervmvrwv9:04337] *** Process received signal ***
[runnervmvrwv9:04337] Signal: Aborted (6)
[runnervmvrwv9:04337] Signal code:  (-6)
[runnervmvrwv9:04337] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f002f445330]
[runnervmvrwv9:04337] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f002f49eb2c]
[runnervmvrwv9:04337] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f002f44527e]
[runnervmvrwv9:04337] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f002f4288ff]
[runnervmvrwv9:04337] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f002f8a5ff5]
[runnervmvrwv9:04337] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f002f8bb0da]
[runnervmvrwv9:04337] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f002f8a5a55]
[runnervmvrwv9:04337] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f002f8a5a6f]
[runnervmvrwv9:04337] [ 8] plumed(+0x146dd)[0x5569f4abc6dd]
[runnervmvrwv9:04337] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f002f42a1ca]
[runnervmvrwv9:04337] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f002f42a28b]
[runnervmvrwv9:04337] [11] plumed(+0x15365)[0x5569f4abd365]
[runnervmvrwv9:04337] *** End of error message ***
</pre>
{% endraw %}
