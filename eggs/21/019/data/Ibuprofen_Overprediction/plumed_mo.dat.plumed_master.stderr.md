**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[fv-az585-767:07277] *** Process received signal ***
[fv-az585-767:07277] Signal: Aborted (6)
[fv-az585-767:07277] Signal code:  (-6)
[fv-az585-767:07277] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd327a42520]
[fv-az585-767:07277] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd327a969fc]
[fv-az585-767:07277] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd327a42476]
[fv-az585-767:07277] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd327a287f3]
[fv-az585-767:07277] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fd327ea2b9e]
[fv-az585-767:07277] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fd327eae20c]
[fv-az585-767:07277] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fd327eae277]
[fv-az585-767:07277] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd327eae52b]
[fv-az585-767:07277] [ 8] plumed_master(+0x14254)[0x562167324254]
[fv-az585-767:07277] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd327a29d90]
[fv-az585-767:07277] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd327a29e40]
[fv-az585-767:07277] [11] plumed_master(+0x14eb5)[0x562167324eb5]
[fv-az585-767:07277] *** End of error message ***
</pre>
{% endraw %}
