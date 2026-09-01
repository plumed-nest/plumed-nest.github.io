**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
Stderr for source:  plumed_trp.dat   
Download: [zipped raw stdout](plumed_trp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_trp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/DLLoader.cpp:50) void* PLMD::DLLoader::load(const std::string&)
Could not load library ../../plumed_so/OPESmetad.so
../../plumed_so/OPESmetad.so: cannot open shared object file: No such file or directory
[runnervmgx7h7:04397] *** Process received signal ***
[runnervmgx7h7:04397] Signal: Aborted (6)
[runnervmgx7h7:04397] Signal code:  (-6)
[runnervmgx7h7:04397] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa35a045330]
[runnervmgx7h7:04397] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa35a09ec0c]
[runnervmgx7h7:04397] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa35a04527e]
[runnervmgx7h7:04397] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa35a0288ff]
[runnervmgx7h7:04397] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa35a4a5ff5]
[runnervmgx7h7:04397] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa35a4bb0da]
[runnervmgx7h7:04397] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa35a4a5a55]
[runnervmgx7h7:04397] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa35a4a5a6f]
[runnervmgx7h7:04397] [ 8] plumed_master(+0x146dd)[0x5561898146dd]
[runnervmgx7h7:04397] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa35a02a1ca]
[runnervmgx7h7:04397] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa35a02a28b]
[runnervmgx7h7:04397] [11] plumed_master(+0x15365)[0x556189815365]
[runnervmgx7h7:04397] *** End of error message ***
</pre>
{% endraw %}
