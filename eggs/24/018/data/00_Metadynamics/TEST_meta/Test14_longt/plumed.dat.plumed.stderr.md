**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07495] *** Process received signal ***
[pkrvm7jw40e0xgp:07495] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07495] Signal code:  (-6)
[pkrvm7jw40e0xgp:07495] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f80e45330]
[pkrvm7jw40e0xgp:07495] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f80e9eb2c]
[pkrvm7jw40e0xgp:07495] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f80e4527e]
[pkrvm7jw40e0xgp:07495] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f80e288ff]
[pkrvm7jw40e0xgp:07495] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f812a5ff5]
[pkrvm7jw40e0xgp:07495] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f812bb0da]
[pkrvm7jw40e0xgp:07495] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f812a5a55]
[pkrvm7jw40e0xgp:07495] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f812a5a6f]
[pkrvm7jw40e0xgp:07495] [ 8] plumed(+0x146dd)[0x55adec2ec6dd]
[pkrvm7jw40e0xgp:07495] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f80e2a1ca]
[pkrvm7jw40e0xgp:07495] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f80e2a28b]
[pkrvm7jw40e0xgp:07495] [11] plumed(+0x15365)[0x55adec2ed365]
[pkrvm7jw40e0xgp:07495] *** End of error message ***
</pre>
{% endraw %}
