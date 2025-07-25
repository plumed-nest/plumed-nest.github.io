**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[pkrvmpptgkbjq6m:10630] *** Process received signal ***
[pkrvmpptgkbjq6m:10630] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10630] Signal code:  (-6)
[pkrvmpptgkbjq6m:10630] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9fb7645330]
[pkrvmpptgkbjq6m:10630] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9fb769eb2c]
[pkrvmpptgkbjq6m:10630] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9fb764527e]
[pkrvmpptgkbjq6m:10630] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9fb76288ff]
[pkrvmpptgkbjq6m:10630] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9fb7aa5ff5]
[pkrvmpptgkbjq6m:10630] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9fb7abb0da]
[pkrvmpptgkbjq6m:10630] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9fb7aa5a55]
[pkrvmpptgkbjq6m:10630] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9fb7aa5a6f]
[pkrvmpptgkbjq6m:10630] [ 8] plumed_master(+0x146dd)[0x55be284336dd]
[pkrvmpptgkbjq6m:10630] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9fb762a1ca]
[pkrvmpptgkbjq6m:10630] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9fb762a28b]
[pkrvmpptgkbjq6m:10630] [11] plumed_master(+0x15365)[0x55be28434365]
[pkrvmpptgkbjq6m:10630] *** End of error message ***
</pre>
{% endraw %}
