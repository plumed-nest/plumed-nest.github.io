**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvm7jw40e0xgp:10681] *** Process received signal ***
[pkrvm7jw40e0xgp:10681] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10681] Signal code:  (-6)
[pkrvm7jw40e0xgp:10681] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5bf7845330]
[pkrvm7jw40e0xgp:10681] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5bf789eb2c]
[pkrvm7jw40e0xgp:10681] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5bf784527e]
[pkrvm7jw40e0xgp:10681] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5bf78288ff]
[pkrvm7jw40e0xgp:10681] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5bf7ca5ff5]
[pkrvm7jw40e0xgp:10681] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5bf7cbb0da]
[pkrvm7jw40e0xgp:10681] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5bf7ca5a55]
[pkrvm7jw40e0xgp:10681] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5bf7ca5a6f]
[pkrvm7jw40e0xgp:10681] [ 8] plumed_master(+0x146dd)[0x557ad08cf6dd]
[pkrvm7jw40e0xgp:10681] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5bf782a1ca]
[pkrvm7jw40e0xgp:10681] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5bf782a28b]
[pkrvm7jw40e0xgp:10681] [11] plumed_master(+0x15365)[0x557ad08d0365]
[pkrvm7jw40e0xgp:10681] *** End of error message ***
</pre>
{% endraw %}
