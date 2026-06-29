**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmmklqx:10196] *** Process received signal ***
[runnervmmklqx:10196] Signal: Aborted (6)
[runnervmmklqx:10196] Signal code:  (-6)
[runnervmmklqx:10196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb626e45330]
[runnervmmklqx:10196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb626e9eb2c]
[runnervmmklqx:10196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb626e4527e]
[runnervmmklqx:10196] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb626e288ff]
[runnervmmklqx:10196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb6272a5ff5]
[runnervmmklqx:10196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb6272bb0da]
[runnervmmklqx:10196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb6272a5a55]
[runnervmmklqx:10196] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb6272a5a6f]
[runnervmmklqx:10196] [ 8] plumed_master(+0x146dd)[0x55dc428cb6dd]
[runnervmmklqx:10196] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb626e2a1ca]
[runnervmmklqx:10196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb626e2a28b]
[runnervmmklqx:10196] [11] plumed_master(+0x15365)[0x55dc428cc365]
[runnervmmklqx:10196] *** End of error message ***
</pre>
{% endraw %}
