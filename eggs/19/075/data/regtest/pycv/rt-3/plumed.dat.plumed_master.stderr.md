**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvm7jw40e0xgp:10472] *** Process received signal ***
[pkrvm7jw40e0xgp:10472] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10472] Signal code:  (-6)
[pkrvm7jw40e0xgp:10472] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdf12845330]
[pkrvm7jw40e0xgp:10472] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdf1289eb2c]
[pkrvm7jw40e0xgp:10472] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdf1284527e]
[pkrvm7jw40e0xgp:10472] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdf128288ff]
[pkrvm7jw40e0xgp:10472] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdf12ca5ff5]
[pkrvm7jw40e0xgp:10472] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdf12cbb0da]
[pkrvm7jw40e0xgp:10472] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdf12ca5a55]
[pkrvm7jw40e0xgp:10472] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdf12ca5a6f]
[pkrvm7jw40e0xgp:10472] [ 8] plumed_master(+0x146dd)[0x55f6b34366dd]
[pkrvm7jw40e0xgp:10472] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdf1282a1ca]
[pkrvm7jw40e0xgp:10472] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdf1282a28b]
[pkrvm7jw40e0xgp:10472] [11] plumed_master(+0x15365)[0x55f6b3437365]
[pkrvm7jw40e0xgp:10472] *** End of error message ***
</pre>
{% endraw %}
