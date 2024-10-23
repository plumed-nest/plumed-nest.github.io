**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[fv-az585-767:04596] *** Process received signal ***
[fv-az585-767:04596] Signal: Aborted (6)
[fv-az585-767:04596] Signal code:  (-6)
[fv-az585-767:04596] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa8c4e42520]
[fv-az585-767:04596] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa8c4e969fc]
[fv-az585-767:04596] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa8c4e42476]
[fv-az585-767:04596] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa8c4e287f3]
[fv-az585-767:04596] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa8c52a2b9e]
[fv-az585-767:04596] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa8c52ae20c]
[fv-az585-767:04596] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa8c52ae277]
[fv-az585-767:04596] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa8c52ae52b]
[fv-az585-767:04596] [ 8] plumed_master(+0x14254)[0x5633124a3254]
[fv-az585-767:04596] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa8c4e29d90]
[fv-az585-767:04596] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa8c4e29e40]
[fv-az585-767:04596] [11] plumed_master(+0x14eb5)[0x5633124a3eb5]
[fv-az585-767:04596] *** End of error message ***
</pre>
{% endraw %}
