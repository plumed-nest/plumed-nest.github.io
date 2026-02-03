**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmkj6or:11466] *** Process received signal ***
[runnervmkj6or:11466] Signal: Aborted (6)
[runnervmkj6or:11466] Signal code:  (-6)
[runnervmkj6or:11466] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd98e845330]
[runnervmkj6or:11466] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd98e89eb2c]
[runnervmkj6or:11466] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd98e84527e]
[runnervmkj6or:11466] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd98e8288ff]
[runnervmkj6or:11466] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd98eca5ff5]
[runnervmkj6or:11466] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd98ecbb0da]
[runnervmkj6or:11466] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd98eca5a55]
[runnervmkj6or:11466] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd98eca5a6f]
[runnervmkj6or:11466] [ 8] plumed(+0x146dd)[0x55c4c29b66dd]
[runnervmkj6or:11466] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd98e82a1ca]
[runnervmkj6or:11466] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd98e82a28b]
[runnervmkj6or:11466] [11] plumed(+0x15365)[0x55c4c29b7365]
[runnervmkj6or:11466] *** End of error message ***
</pre>
{% endraw %}
