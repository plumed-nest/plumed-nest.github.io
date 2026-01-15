**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervmmtnos:34800] *** Process received signal ***
[runnervmmtnos:34800] Signal: Aborted (6)
[runnervmmtnos:34800] Signal code:  (-6)
[runnervmmtnos:34800] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9e76c45330]
[runnervmmtnos:34800] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9e76c9eb2c]
[runnervmmtnos:34800] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9e76c4527e]
[runnervmmtnos:34800] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9e76c288ff]
[runnervmmtnos:34800] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9e770a5ff5]
[runnervmmtnos:34800] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9e770bb0da]
[runnervmmtnos:34800] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9e770a5a55]
[runnervmmtnos:34800] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9e770a5a6f]
[runnervmmtnos:34800] [ 8] plumed_master(+0x146dd)[0x561f0d9386dd]
[runnervmmtnos:34800] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9e76c2a1ca]
[runnervmmtnos:34800] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9e76c2a28b]
[runnervmmtnos:34800] [11] plumed_master(+0x15365)[0x561f0d939365]
[runnervmmtnos:34800] *** End of error message ***
</pre>
{% endraw %}
