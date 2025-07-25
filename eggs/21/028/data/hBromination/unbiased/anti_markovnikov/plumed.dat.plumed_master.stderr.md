**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvmpptgkbjq6m:10519] *** Process received signal ***
[pkrvmpptgkbjq6m:10519] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10519] Signal code:  (-6)
[pkrvmpptgkbjq6m:10519] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f487ee45330]
[pkrvmpptgkbjq6m:10519] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f487ee9eb2c]
[pkrvmpptgkbjq6m:10519] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f487ee4527e]
[pkrvmpptgkbjq6m:10519] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f487ee288ff]
[pkrvmpptgkbjq6m:10519] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f487f2a5ff5]
[pkrvmpptgkbjq6m:10519] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f487f2bb0da]
[pkrvmpptgkbjq6m:10519] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f487f2a5a55]
[pkrvmpptgkbjq6m:10519] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f487f2a5a6f]
[pkrvmpptgkbjq6m:10519] [ 8] plumed_master(+0x146dd)[0x55ac823bf6dd]
[pkrvmpptgkbjq6m:10519] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f487ee2a1ca]
[pkrvmpptgkbjq6m:10519] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f487ee2a28b]
[pkrvmpptgkbjq6m:10519] [11] plumed_master(+0x15365)[0x55ac823c0365]
[pkrvmpptgkbjq6m:10519] *** End of error message ***
</pre>
{% endraw %}
