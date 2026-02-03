**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmkj6or:11312] *** Process received signal ***
[runnervmkj6or:11312] Signal: Aborted (6)
[runnervmkj6or:11312] Signal code:  (-6)
[runnervmkj6or:11312] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f47ab845330]
[runnervmkj6or:11312] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f47ab89eb2c]
[runnervmkj6or:11312] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f47ab84527e]
[runnervmkj6or:11312] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f47ab8288ff]
[runnervmkj6or:11312] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f47abca5ff5]
[runnervmkj6or:11312] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f47abcbb0da]
[runnervmkj6or:11312] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f47abca5a55]
[runnervmkj6or:11312] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f47abca5a6f]
[runnervmkj6or:11312] [ 8] plumed(+0x146dd)[0x55a056fb46dd]
[runnervmkj6or:11312] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f47ab82a1ca]
[runnervmkj6or:11312] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f47ab82a28b]
[runnervmkj6or:11312] [11] plumed(+0x15365)[0x55a056fb5365]
[runnervmkj6or:11312] *** End of error message ***
</pre>
{% endraw %}
