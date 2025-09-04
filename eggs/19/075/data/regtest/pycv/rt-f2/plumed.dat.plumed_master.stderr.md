**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[pkrvm7jw40e0xgp:10576] *** Process received signal ***
[pkrvm7jw40e0xgp:10576] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10576] Signal code:  (-6)
[pkrvm7jw40e0xgp:10576] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe455845330]
[pkrvm7jw40e0xgp:10576] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe45589eb2c]
[pkrvm7jw40e0xgp:10576] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe45584527e]
[pkrvm7jw40e0xgp:10576] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe4558288ff]
[pkrvm7jw40e0xgp:10576] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe455ca5ff5]
[pkrvm7jw40e0xgp:10576] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe455cbb0da]
[pkrvm7jw40e0xgp:10576] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe455ca5a55]
[pkrvm7jw40e0xgp:10576] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe455ca5a6f]
[pkrvm7jw40e0xgp:10576] [ 8] plumed_master(+0x146dd)[0x562b1f5c16dd]
[pkrvm7jw40e0xgp:10576] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe45582a1ca]
[pkrvm7jw40e0xgp:10576] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe45582a28b]
[pkrvm7jw40e0xgp:10576] [11] plumed_master(+0x15365)[0x562b1f5c2365]
[pkrvm7jw40e0xgp:10576] *** End of error message ***
</pre>
{% endraw %}
