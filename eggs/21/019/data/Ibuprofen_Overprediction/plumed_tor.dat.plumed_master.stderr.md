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
[fv-az585-767:07308] *** Process received signal ***
[fv-az585-767:07308] Signal: Aborted (6)
[fv-az585-767:07308] Signal code:  (-6)
[fv-az585-767:07308] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f66c8442520]
[fv-az585-767:07308] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f66c84969fc]
[fv-az585-767:07308] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f66c8442476]
[fv-az585-767:07308] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f66c84287f3]
[fv-az585-767:07308] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f66c88a2b9e]
[fv-az585-767:07308] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f66c88ae20c]
[fv-az585-767:07308] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f66c88ae277]
[fv-az585-767:07308] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f66c88ae52b]
[fv-az585-767:07308] [ 8] plumed_master(+0x14254)[0x560a2161e254]
[fv-az585-767:07308] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f66c8429d90]
[fv-az585-767:07308] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f66c8429e40]
[fv-az585-767:07308] [11] plumed_master(+0x14eb5)[0x560a2161eeb5]
[fv-az585-767:07308] *** End of error message ***
</pre>
{% endraw %}
