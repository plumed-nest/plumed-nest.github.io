**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07288] *** Process received signal ***
[pkrvm7jw40e0xgp:07288] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07288] Signal code:  (-6)
[pkrvm7jw40e0xgp:07288] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f385e845330]
[pkrvm7jw40e0xgp:07288] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f385e89eb2c]
[pkrvm7jw40e0xgp:07288] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f385e84527e]
[pkrvm7jw40e0xgp:07288] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f385e8288ff]
[pkrvm7jw40e0xgp:07288] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f385eca5ff5]
[pkrvm7jw40e0xgp:07288] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f385ecbb0da]
[pkrvm7jw40e0xgp:07288] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f385eca5a55]
[pkrvm7jw40e0xgp:07288] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f385eca5a6f]
[pkrvm7jw40e0xgp:07288] [ 8] plumed(+0x146dd)[0x55e7ae5026dd]
[pkrvm7jw40e0xgp:07288] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f385e82a1ca]
[pkrvm7jw40e0xgp:07288] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f385e82a28b]
[pkrvm7jw40e0xgp:07288] [11] plumed(+0x15365)[0x55e7ae503365]
[pkrvm7jw40e0xgp:07288] *** End of error message ***
</pre>
{% endraw %}
