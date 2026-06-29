**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:06000] *** Process received signal ***
[runnervmmklqx:06000] Signal: Aborted (6)
[runnervmmklqx:06000] Signal code:  (-6)
[runnervmmklqx:06000] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f40cf845330]
[runnervmmklqx:06000] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f40cf89eb2c]
[runnervmmklqx:06000] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f40cf84527e]
[runnervmmklqx:06000] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f40cf8288ff]
[runnervmmklqx:06000] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f40cfca5ff5]
[runnervmmklqx:06000] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f40cfcbb0da]
[runnervmmklqx:06000] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f40cfca5a55]
[runnervmmklqx:06000] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f40cfca5a6f]
[runnervmmklqx:06000] [ 8] plumed_master(+0x146dd)[0x55d8470ee6dd]
[runnervmmklqx:06000] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f40cf82a1ca]
[runnervmmklqx:06000] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f40cf82a28b]
[runnervmmklqx:06000] [11] plumed_master(+0x15365)[0x55d8470ef365]
[runnervmmklqx:06000] *** End of error message ***
</pre>
{% endraw %}
