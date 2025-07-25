**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[pkrvmpptgkbjq6m:12094] *** Process received signal ***
[pkrvmpptgkbjq6m:12094] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12094] Signal code:  (-6)
[pkrvmpptgkbjq6m:12094] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7564645330]
[pkrvmpptgkbjq6m:12094] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f756469eb2c]
[pkrvmpptgkbjq6m:12094] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f756464527e]
[pkrvmpptgkbjq6m:12094] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f75646288ff]
[pkrvmpptgkbjq6m:12094] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7564aa5ff5]
[pkrvmpptgkbjq6m:12094] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7564abb0da]
[pkrvmpptgkbjq6m:12094] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7564aa5a55]
[pkrvmpptgkbjq6m:12094] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7564aa5a6f]
[pkrvmpptgkbjq6m:12094] [ 8] plumed_master(+0x146dd)[0x5585e3ab16dd]
[pkrvmpptgkbjq6m:12094] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f756462a1ca]
[pkrvmpptgkbjq6m:12094] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f756462a28b]
[pkrvmpptgkbjq6m:12094] [11] plumed_master(+0x15365)[0x5585e3ab2365]
[pkrvmpptgkbjq6m:12094] *** End of error message ***
</pre>
{% endraw %}
