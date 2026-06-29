**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:06051] *** Process received signal ***
[runnervmmklqx:06051] Signal: Aborted (6)
[runnervmmklqx:06051] Signal code:  (-6)
[runnervmmklqx:06051] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f481a445330]
[runnervmmklqx:06051] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f481a49eb2c]
[runnervmmklqx:06051] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f481a44527e]
[runnervmmklqx:06051] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f481a4288ff]
[runnervmmklqx:06051] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f481a8a5ff5]
[runnervmmklqx:06051] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f481a8bb0da]
[runnervmmklqx:06051] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f481a8a5a55]
[runnervmmklqx:06051] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f481a8a5a6f]
[runnervmmklqx:06051] [ 8] plumed_master(+0x146dd)[0x55c22b9ad6dd]
[runnervmmklqx:06051] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f481a42a1ca]
[runnervmmklqx:06051] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f481a42a28b]
[runnervmmklqx:06051] [11] plumed_master(+0x15365)[0x55c22b9ae365]
[runnervmmklqx:06051] *** End of error message ***
</pre>
{% endraw %}
