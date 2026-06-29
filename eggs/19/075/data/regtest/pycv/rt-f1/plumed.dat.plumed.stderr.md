**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervmmklqx:10334] *** Process received signal ***
[runnervmmklqx:10334] Signal: Aborted (6)
[runnervmmklqx:10334] Signal code:  (-6)
[runnervmmklqx:10334] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0fbb445330]
[runnervmmklqx:10334] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0fbb49eb2c]
[runnervmmklqx:10334] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0fbb44527e]
[runnervmmklqx:10334] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0fbb4288ff]
[runnervmmklqx:10334] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0fbb8a5ff5]
[runnervmmklqx:10334] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0fbb8bb0da]
[runnervmmklqx:10334] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0fbb8a5a55]
[runnervmmklqx:10334] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0fbb8a5a6f]
[runnervmmklqx:10334] [ 8] plumed(+0x146dd)[0x55b18121e6dd]
[runnervmmklqx:10334] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0fbb42a1ca]
[runnervmmklqx:10334] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0fbb42a28b]
[runnervmmklqx:10334] [11] plumed(+0x15365)[0x55b18121f365]
[runnervmmklqx:10334] *** End of error message ***
</pre>
{% endraw %}
