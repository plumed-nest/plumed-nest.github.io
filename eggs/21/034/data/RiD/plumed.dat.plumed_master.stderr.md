**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[pkrvmq0rgcvqdmg:08921] *** Process received signal ***
[pkrvmq0rgcvqdmg:08921] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08921] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08921] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f96ddc45330]
[pkrvmq0rgcvqdmg:08921] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f96ddc9eb2c]
[pkrvmq0rgcvqdmg:08921] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f96ddc4527e]
[pkrvmq0rgcvqdmg:08921] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f96ddc288ff]
[pkrvmq0rgcvqdmg:08921] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f96de0a5ff5]
[pkrvmq0rgcvqdmg:08921] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f96de0bb0da]
[pkrvmq0rgcvqdmg:08921] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f96de0a5a55]
[pkrvmq0rgcvqdmg:08921] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f96de0a5a6f]
[pkrvmq0rgcvqdmg:08921] [ 8] plumed_master(+0x146dd)[0x55b36aa586dd]
[pkrvmq0rgcvqdmg:08921] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f96ddc2a1ca]
[pkrvmq0rgcvqdmg:08921] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f96ddc2a28b]
[pkrvmq0rgcvqdmg:08921] [11] plumed_master(+0x15365)[0x55b36aa59365]
[pkrvmq0rgcvqdmg:08921] *** End of error message ***
</pre>
{% endraw %}
