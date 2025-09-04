**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07392] *** Process received signal ***
[pkrvm7jw40e0xgp:07392] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07392] Signal code:  (-6)
[pkrvm7jw40e0xgp:07392] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b67e45330]
[pkrvm7jw40e0xgp:07392] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b67e9eb2c]
[pkrvm7jw40e0xgp:07392] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b67e4527e]
[pkrvm7jw40e0xgp:07392] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b67e288ff]
[pkrvm7jw40e0xgp:07392] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b682a5ff5]
[pkrvm7jw40e0xgp:07392] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b682bb0da]
[pkrvm7jw40e0xgp:07392] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b682a5a55]
[pkrvm7jw40e0xgp:07392] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b682a5a6f]
[pkrvm7jw40e0xgp:07392] [ 8] plumed(+0x146dd)[0x564185e1b6dd]
[pkrvm7jw40e0xgp:07392] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b67e2a1ca]
[pkrvm7jw40e0xgp:07392] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b67e2a28b]
[pkrvm7jw40e0xgp:07392] [11] plumed(+0x15365)[0x564185e1c365]
[pkrvm7jw40e0xgp:07392] *** End of error message ***
</pre>
{% endraw %}
