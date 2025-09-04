**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:09091] *** Process received signal ***
[pkrvm7jw40e0xgp:09091] Signal: Aborted (6)
[pkrvm7jw40e0xgp:09091] Signal code:  (-6)
[pkrvm7jw40e0xgp:09091] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4118c45330]
[pkrvm7jw40e0xgp:09091] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4118c9eb2c]
[pkrvm7jw40e0xgp:09091] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4118c4527e]
[pkrvm7jw40e0xgp:09091] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4118c288ff]
[pkrvm7jw40e0xgp:09091] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41190a5ff5]
[pkrvm7jw40e0xgp:09091] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41190bb0da]
[pkrvm7jw40e0xgp:09091] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41190a5a55]
[pkrvm7jw40e0xgp:09091] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41190a5a6f]
[pkrvm7jw40e0xgp:09091] [ 8] plumed_master(+0x146dd)[0x564adfecf6dd]
[pkrvm7jw40e0xgp:09091] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4118c2a1ca]
[pkrvm7jw40e0xgp:09091] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4118c2a28b]
[pkrvm7jw40e0xgp:09091] [11] plumed_master(+0x15365)[0x564adfed0365]
[pkrvm7jw40e0xgp:09091] *** End of error message ***
</pre>
{% endraw %}
