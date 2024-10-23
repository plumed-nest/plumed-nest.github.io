**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az585-767:10447] *** Process received signal ***
[fv-az585-767:10447] Signal: Aborted (6)
[fv-az585-767:10447] Signal code:  (-6)
[fv-az585-767:10447] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3332a42520]
[fv-az585-767:10447] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3332a969fc]
[fv-az585-767:10447] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3332a42476]
[fv-az585-767:10447] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3332a287f3]
[fv-az585-767:10447] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3332ea2b9e]
[fv-az585-767:10447] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3332eae20c]
[fv-az585-767:10447] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3332eae277]
[fv-az585-767:10447] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3332eae52b]
[fv-az585-767:10447] [ 8] plumed_master(+0x14254)[0x55a51bbef254]
[fv-az585-767:10447] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3332a29d90]
[fv-az585-767:10447] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3332a29e40]
[fv-az585-767:10447] [11] plumed_master(+0x14eb5)[0x55a51bbefeb5]
[fv-az585-767:10447] *** End of error message ***
</pre>
{% endraw %}
