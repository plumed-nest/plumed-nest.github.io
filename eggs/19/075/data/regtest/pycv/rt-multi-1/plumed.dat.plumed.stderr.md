**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmq0rgcvqdmg:12059] *** Process received signal ***
[pkrvmq0rgcvqdmg:12059] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12059] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12059] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcec1245330]
[pkrvmq0rgcvqdmg:12059] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcec129eb2c]
[pkrvmq0rgcvqdmg:12059] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcec124527e]
[pkrvmq0rgcvqdmg:12059] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcec12288ff]
[pkrvmq0rgcvqdmg:12059] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcec16a5ff5]
[pkrvmq0rgcvqdmg:12059] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcec16bb0da]
[pkrvmq0rgcvqdmg:12059] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcec16a5a55]
[pkrvmq0rgcvqdmg:12059] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcec16a5a6f]
[pkrvmq0rgcvqdmg:12059] [ 8] plumed(+0x146dd)[0x55d43922e6dd]
[pkrvmq0rgcvqdmg:12059] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcec122a1ca]
[pkrvmq0rgcvqdmg:12059] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcec122a28b]
[pkrvmq0rgcvqdmg:12059] [11] plumed(+0x15365)[0x55d43922f365]
[pkrvmq0rgcvqdmg:12059] *** End of error message ***
</pre>
{% endraw %}
