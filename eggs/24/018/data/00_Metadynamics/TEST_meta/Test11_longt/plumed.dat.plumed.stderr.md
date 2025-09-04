**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07340] *** Process received signal ***
[pkrvm7jw40e0xgp:07340] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07340] Signal code:  (-6)
[pkrvm7jw40e0xgp:07340] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0209645330]
[pkrvm7jw40e0xgp:07340] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f020969eb2c]
[pkrvm7jw40e0xgp:07340] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f020964527e]
[pkrvm7jw40e0xgp:07340] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02096288ff]
[pkrvm7jw40e0xgp:07340] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0209aa5ff5]
[pkrvm7jw40e0xgp:07340] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0209abb0da]
[pkrvm7jw40e0xgp:07340] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0209aa5a55]
[pkrvm7jw40e0xgp:07340] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0209aa5a6f]
[pkrvm7jw40e0xgp:07340] [ 8] plumed(+0x146dd)[0x55b700d436dd]
[pkrvm7jw40e0xgp:07340] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f020962a1ca]
[pkrvm7jw40e0xgp:07340] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f020962a28b]
[pkrvm7jw40e0xgp:07340] [11] plumed(+0x15365)[0x55b700d44365]
[pkrvm7jw40e0xgp:07340] *** End of error message ***
</pre>
{% endraw %}
