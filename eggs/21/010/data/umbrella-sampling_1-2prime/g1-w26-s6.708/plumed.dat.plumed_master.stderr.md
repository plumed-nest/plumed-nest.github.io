**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w26-s6.708/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:09246] *** Process received signal ***
[pkrvm7jw40e0xgp:09246] Signal: Aborted (6)
[pkrvm7jw40e0xgp:09246] Signal code:  (-6)
[pkrvm7jw40e0xgp:09246] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6e7d845330]
[pkrvm7jw40e0xgp:09246] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6e7d89eb2c]
[pkrvm7jw40e0xgp:09246] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6e7d84527e]
[pkrvm7jw40e0xgp:09246] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6e7d8288ff]
[pkrvm7jw40e0xgp:09246] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6e7dca5ff5]
[pkrvm7jw40e0xgp:09246] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6e7dcbb0da]
[pkrvm7jw40e0xgp:09246] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6e7dca5a55]
[pkrvm7jw40e0xgp:09246] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6e7dca5a6f]
[pkrvm7jw40e0xgp:09246] [ 8] plumed_master(+0x146dd)[0x55c897ec46dd]
[pkrvm7jw40e0xgp:09246] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6e7d82a1ca]
[pkrvm7jw40e0xgp:09246] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6e7d82a28b]
[pkrvm7jw40e0xgp:09246] [11] plumed_master(+0x15365)[0x55c897ec5365]
[pkrvm7jw40e0xgp:09246] *** End of error message ***
</pre>
{% endraw %}
