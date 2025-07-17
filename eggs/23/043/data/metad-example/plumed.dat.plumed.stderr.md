**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvmq0rgcvqdmg:08122] *** Process received signal ***
[pkrvmq0rgcvqdmg:08122] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08122] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08122] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcefe245330]
[pkrvmq0rgcvqdmg:08122] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcefe29eb2c]
[pkrvmq0rgcvqdmg:08122] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcefe24527e]
[pkrvmq0rgcvqdmg:08122] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcefe2288ff]
[pkrvmq0rgcvqdmg:08122] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcefe6a5ff5]
[pkrvmq0rgcvqdmg:08122] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcefe6bb0da]
[pkrvmq0rgcvqdmg:08122] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcefe6a5a55]
[pkrvmq0rgcvqdmg:08122] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcefe6a5a6f]
[pkrvmq0rgcvqdmg:08122] [ 8] plumed(+0x146dd)[0x560a4d33e6dd]
[pkrvmq0rgcvqdmg:08122] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcefe22a1ca]
[pkrvmq0rgcvqdmg:08122] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcefe22a28b]
[pkrvmq0rgcvqdmg:08122] [11] plumed(+0x15365)[0x560a4d33f365]
[pkrvmq0rgcvqdmg:08122] *** End of error message ***
</pre>
{% endraw %}
