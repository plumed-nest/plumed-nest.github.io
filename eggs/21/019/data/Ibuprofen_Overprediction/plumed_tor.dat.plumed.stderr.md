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
[fv-az585-767:07300] *** Process received signal ***
[fv-az585-767:07300] Signal: Aborted (6)
[fv-az585-767:07300] Signal code:  (-6)
[fv-az585-767:07300] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fdb42442520]
[fv-az585-767:07300] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fdb424969fc]
[fv-az585-767:07300] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fdb42442476]
[fv-az585-767:07300] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fdb424287f3]
[fv-az585-767:07300] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fdb428a2b9e]
[fv-az585-767:07300] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fdb428ae20c]
[fv-az585-767:07300] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fdb428ae277]
[fv-az585-767:07300] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fdb428ae52b]
[fv-az585-767:07300] [ 8] plumed(+0x14254)[0x5564e49e1254]
[fv-az585-767:07300] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fdb42429d90]
[fv-az585-767:07300] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fdb42429e40]
[fv-az585-767:07300] [11] plumed(+0x14eb5)[0x5564e49e1eb5]
[fv-az585-767:07300] *** End of error message ***
</pre>
{% endraw %}
