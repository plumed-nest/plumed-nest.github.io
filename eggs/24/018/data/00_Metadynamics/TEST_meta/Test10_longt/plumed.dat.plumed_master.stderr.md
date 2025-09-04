**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07304] *** Process received signal ***
[pkrvm7jw40e0xgp:07304] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07304] Signal code:  (-6)
[pkrvm7jw40e0xgp:07304] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb6d3045330]
[pkrvm7jw40e0xgp:07304] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb6d309eb2c]
[pkrvm7jw40e0xgp:07304] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb6d304527e]
[pkrvm7jw40e0xgp:07304] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb6d30288ff]
[pkrvm7jw40e0xgp:07304] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb6d34a5ff5]
[pkrvm7jw40e0xgp:07304] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb6d34bb0da]
[pkrvm7jw40e0xgp:07304] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb6d34a5a55]
[pkrvm7jw40e0xgp:07304] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb6d34a5a6f]
[pkrvm7jw40e0xgp:07304] [ 8] plumed_master(+0x146dd)[0x55808845b6dd]
[pkrvm7jw40e0xgp:07304] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb6d302a1ca]
[pkrvm7jw40e0xgp:07304] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb6d302a28b]
[pkrvm7jw40e0xgp:07304] [11] plumed_master(+0x15365)[0x55808845c365]
[pkrvm7jw40e0xgp:07304] *** End of error message ***
</pre>
{% endraw %}
