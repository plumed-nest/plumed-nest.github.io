**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervmkj6or:11431] *** Process received signal ***
[runnervmkj6or:11431] Signal: Aborted (6)
[runnervmkj6or:11431] Signal code:  (-6)
[runnervmkj6or:11431] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f918d445330]
[runnervmkj6or:11431] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f918d49eb2c]
[runnervmkj6or:11431] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f918d44527e]
[runnervmkj6or:11431] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f918d4288ff]
[runnervmkj6or:11431] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f918d8a5ff5]
[runnervmkj6or:11431] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f918d8bb0da]
[runnervmkj6or:11431] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f918d8a5a55]
[runnervmkj6or:11431] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f918d8a5a6f]
[runnervmkj6or:11431] [ 8] plumed_master(+0x146dd)[0x55684effa6dd]
[runnervmkj6or:11431] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f918d42a1ca]
[runnervmkj6or:11431] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f918d42a28b]
[runnervmkj6or:11431] [11] plumed_master(+0x15365)[0x55684effb365]
[runnervmkj6or:11431] *** End of error message ***
</pre>
{% endraw %}
