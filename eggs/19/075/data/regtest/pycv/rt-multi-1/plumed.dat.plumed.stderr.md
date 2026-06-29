**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmmklqx:10594] *** Process received signal ***
[runnervmmklqx:10594] Signal: Aborted (6)
[runnervmmklqx:10594] Signal code:  (-6)
[runnervmmklqx:10594] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff180245330]
[runnervmmklqx:10594] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff18029eb2c]
[runnervmmklqx:10594] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff18024527e]
[runnervmmklqx:10594] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1802288ff]
[runnervmmklqx:10594] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1806a5ff5]
[runnervmmklqx:10594] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1806bb0da]
[runnervmmklqx:10594] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1806a5a55]
[runnervmmklqx:10594] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1806a5a6f]
[runnervmmklqx:10594] [ 8] plumed(+0x146dd)[0x55b34c4ea6dd]
[runnervmmklqx:10594] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff18022a1ca]
[runnervmmklqx:10594] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff18022a28b]
[runnervmmklqx:10594] [11] plumed(+0x15365)[0x55b34c4eb365]
[runnervmmklqx:10594] *** End of error message ***
</pre>
{% endraw %}
