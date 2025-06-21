**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[pkrvmxyh4eaekms:13892] *** Process received signal ***
[pkrvmxyh4eaekms:13892] Signal: Aborted (6)
[pkrvmxyh4eaekms:13892] Signal code:  (-6)
[pkrvmxyh4eaekms:13892] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4e25a45330]
[pkrvmxyh4eaekms:13892] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4e25a9eb2c]
[pkrvmxyh4eaekms:13892] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4e25a4527e]
[pkrvmxyh4eaekms:13892] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4e25a288ff]
[pkrvmxyh4eaekms:13892] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4e25ea5ff5]
[pkrvmxyh4eaekms:13892] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4e25ebb0da]
[pkrvmxyh4eaekms:13892] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4e25ea5a55]
[pkrvmxyh4eaekms:13892] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4e25ea5a6f]
[pkrvmxyh4eaekms:13892] [ 8] plumed_master(+0x146dd)[0x5584ae8ce6dd]
[pkrvmxyh4eaekms:13892] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4e25a2a1ca]
[pkrvmxyh4eaekms:13892] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4e25a2a28b]
[pkrvmxyh4eaekms:13892] [11] plumed_master(+0x15365)[0x5584ae8cf365]
[pkrvmxyh4eaekms:13892] *** End of error message ***
</pre>
{% endraw %}
