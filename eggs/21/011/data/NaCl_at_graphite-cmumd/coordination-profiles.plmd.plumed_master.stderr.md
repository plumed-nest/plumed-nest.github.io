**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[pkrvm7jw40e0xgp:12109] *** Process received signal ***
[pkrvm7jw40e0xgp:12109] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12109] Signal code:  (-6)
[pkrvm7jw40e0xgp:12109] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f88245330]
[pkrvm7jw40e0xgp:12109] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f8829eb2c]
[pkrvm7jw40e0xgp:12109] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f8824527e]
[pkrvm7jw40e0xgp:12109] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f882288ff]
[pkrvm7jw40e0xgp:12109] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f886a5ff5]
[pkrvm7jw40e0xgp:12109] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f886bb0da]
[pkrvm7jw40e0xgp:12109] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f886a5a55]
[pkrvm7jw40e0xgp:12109] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f886a5a6f]
[pkrvm7jw40e0xgp:12109] [ 8] plumed_master(+0x146dd)[0x55a13fe666dd]
[pkrvm7jw40e0xgp:12109] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f8822a1ca]
[pkrvm7jw40e0xgp:12109] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f8822a28b]
[pkrvm7jw40e0xgp:12109] [11] plumed_master(+0x15365)[0x55a13fe67365]
[pkrvm7jw40e0xgp:12109] *** End of error message ***
</pre>
{% endraw %}
