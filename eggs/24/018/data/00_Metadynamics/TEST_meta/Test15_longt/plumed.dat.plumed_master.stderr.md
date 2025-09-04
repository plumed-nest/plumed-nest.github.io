**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvm7jw40e0xgp:07562] *** Process received signal ***
[pkrvm7jw40e0xgp:07562] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07562] Signal code:  (-6)
[pkrvm7jw40e0xgp:07562] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7648645330]
[pkrvm7jw40e0xgp:07562] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f764869eb2c]
[pkrvm7jw40e0xgp:07562] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f764864527e]
[pkrvm7jw40e0xgp:07562] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76486288ff]
[pkrvm7jw40e0xgp:07562] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7648aa5ff5]
[pkrvm7jw40e0xgp:07562] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7648abb0da]
[pkrvm7jw40e0xgp:07562] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7648aa5a55]
[pkrvm7jw40e0xgp:07562] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7648aa5a6f]
[pkrvm7jw40e0xgp:07562] [ 8] plumed_master(+0x146dd)[0x559df59666dd]
[pkrvm7jw40e0xgp:07562] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f764862a1ca]
[pkrvm7jw40e0xgp:07562] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f764862a28b]
[pkrvm7jw40e0xgp:07562] [11] plumed_master(+0x15365)[0x559df5967365]
[pkrvm7jw40e0xgp:07562] *** End of error message ***
</pre>
{% endraw %}
