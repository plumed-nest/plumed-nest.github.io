**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvm7jw40e0xgp:10716] *** Process received signal ***
[pkrvm7jw40e0xgp:10716] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10716] Signal code:  (-6)
[pkrvm7jw40e0xgp:10716] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0e6b045330]
[pkrvm7jw40e0xgp:10716] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0e6b09eb2c]
[pkrvm7jw40e0xgp:10716] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0e6b04527e]
[pkrvm7jw40e0xgp:10716] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0e6b0288ff]
[pkrvm7jw40e0xgp:10716] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0e6b4a5ff5]
[pkrvm7jw40e0xgp:10716] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0e6b4bb0da]
[pkrvm7jw40e0xgp:10716] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0e6b4a5a55]
[pkrvm7jw40e0xgp:10716] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0e6b4a5a6f]
[pkrvm7jw40e0xgp:10716] [ 8] plumed(+0x146dd)[0x55ec20bc86dd]
[pkrvm7jw40e0xgp:10716] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0e6b02a1ca]
[pkrvm7jw40e0xgp:10716] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0e6b02a28b]
[pkrvm7jw40e0xgp:10716] [11] plumed(+0x15365)[0x55ec20bc9365]
[pkrvm7jw40e0xgp:10716] *** End of error message ***
</pre>
{% endraw %}
