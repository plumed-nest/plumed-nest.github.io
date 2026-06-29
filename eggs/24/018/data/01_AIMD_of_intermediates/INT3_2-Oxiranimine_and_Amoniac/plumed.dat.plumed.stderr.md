**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:06709] *** Process received signal ***
[runnervmmklqx:06709] Signal: Aborted (6)
[runnervmmklqx:06709] Signal code:  (-6)
[runnervmmklqx:06709] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fae9f445330]
[runnervmmklqx:06709] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fae9f49eb2c]
[runnervmmklqx:06709] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fae9f44527e]
[runnervmmklqx:06709] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fae9f4288ff]
[runnervmmklqx:06709] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fae9f8a5ff5]
[runnervmmklqx:06709] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fae9f8bb0da]
[runnervmmklqx:06709] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fae9f8a5a55]
[runnervmmklqx:06709] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fae9f8a5a6f]
[runnervmmklqx:06709] [ 8] plumed(+0x146dd)[0x5650b88c16dd]
[runnervmmklqx:06709] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fae9f42a1ca]
[runnervmmklqx:06709] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fae9f42a28b]
[runnervmmklqx:06709] [11] plumed(+0x15365)[0x5650b88c2365]
[runnervmmklqx:06709] *** End of error message ***
</pre>
{% endraw %}
