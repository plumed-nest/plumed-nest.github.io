**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07546] *** Process received signal ***
[pkrvm7jw40e0xgp:07546] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07546] Signal code:  (-6)
[pkrvm7jw40e0xgp:07546] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f79abc45330]
[pkrvm7jw40e0xgp:07546] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f79abc9eb2c]
[pkrvm7jw40e0xgp:07546] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f79abc4527e]
[pkrvm7jw40e0xgp:07546] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79abc288ff]
[pkrvm7jw40e0xgp:07546] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f79ac0a5ff5]
[pkrvm7jw40e0xgp:07546] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f79ac0bb0da]
[pkrvm7jw40e0xgp:07546] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f79ac0a5a55]
[pkrvm7jw40e0xgp:07546] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f79ac0a5a6f]
[pkrvm7jw40e0xgp:07546] [ 8] plumed(+0x146dd)[0x56176f1cb6dd]
[pkrvm7jw40e0xgp:07546] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f79abc2a1ca]
[pkrvm7jw40e0xgp:07546] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f79abc2a28b]
[pkrvm7jw40e0xgp:07546] [11] plumed(+0x15365)[0x56176f1cc365]
[pkrvm7jw40e0xgp:07546] *** End of error message ***
</pre>
{% endraw %}
