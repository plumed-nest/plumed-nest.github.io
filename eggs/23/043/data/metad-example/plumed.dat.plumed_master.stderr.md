**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvm7jw40e0xgp:07375] *** Process received signal ***
[pkrvm7jw40e0xgp:07375] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07375] Signal code:  (-6)
[pkrvm7jw40e0xgp:07375] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9486445330]
[pkrvm7jw40e0xgp:07375] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f948649eb2c]
[pkrvm7jw40e0xgp:07375] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f948644527e]
[pkrvm7jw40e0xgp:07375] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f94864288ff]
[pkrvm7jw40e0xgp:07375] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f94868a5ff5]
[pkrvm7jw40e0xgp:07375] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f94868bb0da]
[pkrvm7jw40e0xgp:07375] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f94868a5a55]
[pkrvm7jw40e0xgp:07375] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f94868a5a6f]
[pkrvm7jw40e0xgp:07375] [ 8] plumed_master(+0x146dd)[0x55c510c606dd]
[pkrvm7jw40e0xgp:07375] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f948642a1ca]
[pkrvm7jw40e0xgp:07375] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f948642a28b]
[pkrvm7jw40e0xgp:07375] [11] plumed_master(+0x15365)[0x55c510c61365]
[pkrvm7jw40e0xgp:07375] *** End of error message ***
</pre>
{% endraw %}
