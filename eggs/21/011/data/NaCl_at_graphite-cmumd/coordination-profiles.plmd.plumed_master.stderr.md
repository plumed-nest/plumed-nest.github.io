**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervmvrwv9:09102] *** Process received signal ***
[runnervmvrwv9:09102] Signal: Aborted (6)
[runnervmvrwv9:09102] Signal code:  (-6)
[runnervmvrwv9:09102] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd629445330]
[runnervmvrwv9:09102] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd62949eb2c]
[runnervmvrwv9:09102] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd62944527e]
[runnervmvrwv9:09102] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6294288ff]
[runnervmvrwv9:09102] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6298a5ff5]
[runnervmvrwv9:09102] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6298bb0da]
[runnervmvrwv9:09102] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6298a5a55]
[runnervmvrwv9:09102] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6298a5a6f]
[runnervmvrwv9:09102] [ 8] plumed_master(+0x146dd)[0x563414f116dd]
[runnervmvrwv9:09102] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd62942a1ca]
[runnervmvrwv9:09102] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd62942a28b]
[runnervmvrwv9:09102] [11] plumed_master(+0x15365)[0x563414f12365]
[runnervmvrwv9:09102] *** End of error message ***
</pre>
{% endraw %}
