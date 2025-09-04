**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[pkrvm7jw40e0xgp:12674] *** Process received signal ***
[pkrvm7jw40e0xgp:12674] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12674] Signal code:  (-6)
[pkrvm7jw40e0xgp:12674] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7febeec45330]
[pkrvm7jw40e0xgp:12674] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7febeec9eb2c]
[pkrvm7jw40e0xgp:12674] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7febeec4527e]
[pkrvm7jw40e0xgp:12674] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7febeec288ff]
[pkrvm7jw40e0xgp:12674] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7febef0a5ff5]
[pkrvm7jw40e0xgp:12674] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7febef0bb0da]
[pkrvm7jw40e0xgp:12674] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7febef0a5a55]
[pkrvm7jw40e0xgp:12674] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7febef0a5a6f]
[pkrvm7jw40e0xgp:12674] [ 8] plumed(+0x146dd)[0x55845259c6dd]
[pkrvm7jw40e0xgp:12674] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7febeec2a1ca]
[pkrvm7jw40e0xgp:12674] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7febeec2a28b]
[pkrvm7jw40e0xgp:12674] [11] plumed(+0x15365)[0x55845259d365]
[pkrvm7jw40e0xgp:12674] *** End of error message ***
</pre>
{% endraw %}
