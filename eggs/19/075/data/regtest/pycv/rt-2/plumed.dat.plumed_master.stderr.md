**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az585-767:10416] *** Process received signal ***
[fv-az585-767:10416] Signal: Aborted (6)
[fv-az585-767:10416] Signal code:  (-6)
[fv-az585-767:10416] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7efe7ba42520]
[fv-az585-767:10416] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7efe7ba969fc]
[fv-az585-767:10416] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7efe7ba42476]
[fv-az585-767:10416] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7efe7ba287f3]
[fv-az585-767:10416] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7efe7bea2b9e]
[fv-az585-767:10416] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7efe7beae20c]
[fv-az585-767:10416] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7efe7beae277]
[fv-az585-767:10416] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7efe7beae52b]
[fv-az585-767:10416] [ 8] plumed_master(+0x14254)[0x55fadc7ef254]
[fv-az585-767:10416] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7efe7ba29d90]
[fv-az585-767:10416] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7efe7ba29e40]
[fv-az585-767:10416] [11] plumed_master(+0x14eb5)[0x55fadc7efeb5]
[fv-az585-767:10416] *** End of error message ***
</pre>
{% endraw %}
