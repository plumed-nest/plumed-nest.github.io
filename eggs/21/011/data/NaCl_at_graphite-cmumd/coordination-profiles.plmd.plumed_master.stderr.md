**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[pkrvmq0rgcvqdmg:12176] *** Process received signal ***
[pkrvmq0rgcvqdmg:12176] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12176] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12176] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f135d845330]
[pkrvmq0rgcvqdmg:12176] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f135d89eb2c]
[pkrvmq0rgcvqdmg:12176] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f135d84527e]
[pkrvmq0rgcvqdmg:12176] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f135d8288ff]
[pkrvmq0rgcvqdmg:12176] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f135dca5ff5]
[pkrvmq0rgcvqdmg:12176] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f135dcbb0da]
[pkrvmq0rgcvqdmg:12176] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f135dca5a55]
[pkrvmq0rgcvqdmg:12176] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f135dca5a6f]
[pkrvmq0rgcvqdmg:12176] [ 8] plumed_master(+0x146dd)[0x559d2b1516dd]
[pkrvmq0rgcvqdmg:12176] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f135d82a1ca]
[pkrvmq0rgcvqdmg:12176] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f135d82a28b]
[pkrvmq0rgcvqdmg:12176] [11] plumed_master(+0x15365)[0x559d2b152365]
[pkrvmq0rgcvqdmg:12176] *** End of error message ***
</pre>
{% endraw %}
