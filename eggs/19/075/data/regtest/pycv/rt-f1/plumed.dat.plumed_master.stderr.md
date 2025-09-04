**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[pkrvm7jw40e0xgp:10526] *** Process received signal ***
[pkrvm7jw40e0xgp:10526] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10526] Signal code:  (-6)
[pkrvm7jw40e0xgp:10526] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d6c445330]
[pkrvm7jw40e0xgp:10526] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d6c49eb2c]
[pkrvm7jw40e0xgp:10526] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d6c44527e]
[pkrvm7jw40e0xgp:10526] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d6c4288ff]
[pkrvm7jw40e0xgp:10526] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d6c8a5ff5]
[pkrvm7jw40e0xgp:10526] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d6c8bb0da]
[pkrvm7jw40e0xgp:10526] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d6c8a5a55]
[pkrvm7jw40e0xgp:10526] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d6c8a5a6f]
[pkrvm7jw40e0xgp:10526] [ 8] plumed_master(+0x146dd)[0x559a3c0e06dd]
[pkrvm7jw40e0xgp:10526] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d6c42a1ca]
[pkrvm7jw40e0xgp:10526] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d6c42a28b]
[pkrvm7jw40e0xgp:10526] [11] plumed_master(+0x15365)[0x559a3c0e1365]
[pkrvm7jw40e0xgp:10526] *** End of error message ***
</pre>
{% endraw %}
