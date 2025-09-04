**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[pkrvm7jw40e0xgp:12639] *** Process received signal ***
[pkrvm7jw40e0xgp:12639] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12639] Signal code:  (-6)
[pkrvm7jw40e0xgp:12639] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd3e7e45330]
[pkrvm7jw40e0xgp:12639] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd3e7e9eb2c]
[pkrvm7jw40e0xgp:12639] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd3e7e4527e]
[pkrvm7jw40e0xgp:12639] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd3e7e288ff]
[pkrvm7jw40e0xgp:12639] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd3e82a5ff5]
[pkrvm7jw40e0xgp:12639] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd3e82bb0da]
[pkrvm7jw40e0xgp:12639] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd3e82a5a55]
[pkrvm7jw40e0xgp:12639] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd3e82a5a6f]
[pkrvm7jw40e0xgp:12639] [ 8] plumed_master(+0x146dd)[0x55a1c0d9f6dd]
[pkrvm7jw40e0xgp:12639] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd3e7e2a1ca]
[pkrvm7jw40e0xgp:12639] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd3e7e2a28b]
[pkrvm7jw40e0xgp:12639] [11] plumed_master(+0x15365)[0x55a1c0da0365]
[pkrvm7jw40e0xgp:12639] *** End of error message ***
</pre>
{% endraw %}
