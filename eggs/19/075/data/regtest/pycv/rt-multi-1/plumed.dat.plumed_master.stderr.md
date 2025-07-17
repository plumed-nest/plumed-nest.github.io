**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmq0rgcvqdmg:12075] *** Process received signal ***
[pkrvmq0rgcvqdmg:12075] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12075] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12075] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdf21645330]
[pkrvmq0rgcvqdmg:12075] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdf2169eb2c]
[pkrvmq0rgcvqdmg:12075] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdf2164527e]
[pkrvmq0rgcvqdmg:12075] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdf216288ff]
[pkrvmq0rgcvqdmg:12075] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdf21aa5ff5]
[pkrvmq0rgcvqdmg:12075] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdf21abb0da]
[pkrvmq0rgcvqdmg:12075] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdf21aa5a55]
[pkrvmq0rgcvqdmg:12075] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdf21aa5a6f]
[pkrvmq0rgcvqdmg:12075] [ 8] plumed_master(+0x146dd)[0x558d9457b6dd]
[pkrvmq0rgcvqdmg:12075] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdf2162a1ca]
[pkrvmq0rgcvqdmg:12075] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdf2162a28b]
[pkrvmq0rgcvqdmg:12075] [11] plumed_master(+0x15365)[0x558d9457c365]
[pkrvmq0rgcvqdmg:12075] *** End of error message ***
</pre>
{% endraw %}
