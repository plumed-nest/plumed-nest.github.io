**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[pkrvmq0rgcvqdmg:12945] *** Process received signal ***
[pkrvmq0rgcvqdmg:12945] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12945] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12945] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef89045330]
[pkrvmq0rgcvqdmg:12945] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef8909eb2c]
[pkrvmq0rgcvqdmg:12945] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef8904527e]
[pkrvmq0rgcvqdmg:12945] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef890288ff]
[pkrvmq0rgcvqdmg:12945] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef894a5ff5]
[pkrvmq0rgcvqdmg:12945] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef894bb0da]
[pkrvmq0rgcvqdmg:12945] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef894a5a55]
[pkrvmq0rgcvqdmg:12945] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef894a5a6f]
[pkrvmq0rgcvqdmg:12945] [ 8] plumed(+0x146dd)[0x55a3ffdf46dd]
[pkrvmq0rgcvqdmg:12945] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef8902a1ca]
[pkrvmq0rgcvqdmg:12945] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef8902a28b]
[pkrvmq0rgcvqdmg:12945] [11] plumed(+0x15365)[0x55a3ffdf5365]
[pkrvmq0rgcvqdmg:12945] *** End of error message ***
</pre>
{% endraw %}
