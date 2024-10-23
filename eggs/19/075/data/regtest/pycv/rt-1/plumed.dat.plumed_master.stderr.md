**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az585-767:10385] *** Process received signal ***
[fv-az585-767:10385] Signal: Aborted (6)
[fv-az585-767:10385] Signal code:  (-6)
[fv-az585-767:10385] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb348442520]
[fv-az585-767:10385] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb3484969fc]
[fv-az585-767:10385] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb348442476]
[fv-az585-767:10385] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb3484287f3]
[fv-az585-767:10385] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb3488a2b9e]
[fv-az585-767:10385] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb3488ae20c]
[fv-az585-767:10385] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb3488ae277]
[fv-az585-767:10385] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb3488ae52b]
[fv-az585-767:10385] [ 8] plumed_master(+0x14254)[0x560721aca254]
[fv-az585-767:10385] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb348429d90]
[fv-az585-767:10385] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb348429e40]
[fv-az585-767:10385] [11] plumed_master(+0x14eb5)[0x560721acaeb5]
[fv-az585-767:10385] *** End of error message ***
</pre>
{% endraw %}
