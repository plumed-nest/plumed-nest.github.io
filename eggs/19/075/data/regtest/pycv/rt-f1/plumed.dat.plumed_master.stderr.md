**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[pkrvmq0rgcvqdmg:11819] *** Process received signal ***
[pkrvmq0rgcvqdmg:11819] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11819] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11819] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6b01a45330]
[pkrvmq0rgcvqdmg:11819] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6b01a9eb2c]
[pkrvmq0rgcvqdmg:11819] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6b01a4527e]
[pkrvmq0rgcvqdmg:11819] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6b01a288ff]
[pkrvmq0rgcvqdmg:11819] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6b01ea5ff5]
[pkrvmq0rgcvqdmg:11819] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6b01ebb0da]
[pkrvmq0rgcvqdmg:11819] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6b01ea5a55]
[pkrvmq0rgcvqdmg:11819] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6b01ea5a6f]
[pkrvmq0rgcvqdmg:11819] [ 8] plumed_master(+0x146dd)[0x556f4b66e6dd]
[pkrvmq0rgcvqdmg:11819] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6b01a2a1ca]
[pkrvmq0rgcvqdmg:11819] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6b01a2a28b]
[pkrvmq0rgcvqdmg:11819] [11] plumed_master(+0x15365)[0x556f4b66f365]
[pkrvmq0rgcvqdmg:11819] *** End of error message ***
</pre>
{% endraw %}
