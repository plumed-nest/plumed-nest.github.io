**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[pkrvm7jw40e0xgp:12690] *** Process received signal ***
[pkrvm7jw40e0xgp:12690] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12690] Signal code:  (-6)
[pkrvm7jw40e0xgp:12690] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f58d6c45330]
[pkrvm7jw40e0xgp:12690] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f58d6c9eb2c]
[pkrvm7jw40e0xgp:12690] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f58d6c4527e]
[pkrvm7jw40e0xgp:12690] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f58d6c288ff]
[pkrvm7jw40e0xgp:12690] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f58d70a5ff5]
[pkrvm7jw40e0xgp:12690] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f58d70bb0da]
[pkrvm7jw40e0xgp:12690] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f58d70a5a55]
[pkrvm7jw40e0xgp:12690] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f58d70a5a6f]
[pkrvm7jw40e0xgp:12690] [ 8] plumed_master(+0x146dd)[0x56064539f6dd]
[pkrvm7jw40e0xgp:12690] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f58d6c2a1ca]
[pkrvm7jw40e0xgp:12690] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f58d6c2a28b]
[pkrvm7jw40e0xgp:12690] [11] plumed_master(+0x15365)[0x5606453a0365]
[pkrvm7jw40e0xgp:12690] *** End of error message ***
</pre>
{% endraw %}
