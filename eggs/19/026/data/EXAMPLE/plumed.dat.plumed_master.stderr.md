**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervmmklqx:12221] *** Process received signal ***
[runnervmmklqx:12221] Signal: Aborted (6)
[runnervmmklqx:12221] Signal code:  (-6)
[runnervmmklqx:12221] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d04845330]
[runnervmmklqx:12221] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d0489eb2c]
[runnervmmklqx:12221] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d0484527e]
[runnervmmklqx:12221] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d048288ff]
[runnervmmklqx:12221] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d04ca5ff5]
[runnervmmklqx:12221] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d04cbb0da]
[runnervmmklqx:12221] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d04ca5a55]
[runnervmmklqx:12221] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d04ca5a6f]
[runnervmmklqx:12221] [ 8] plumed_master(+0x146dd)[0x55c11a58b6dd]
[runnervmmklqx:12221] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d0482a1ca]
[runnervmmklqx:12221] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d0482a28b]
[runnervmmklqx:12221] [11] plumed_master(+0x15365)[0x55c11a58c365]
[runnervmmklqx:12221] *** End of error message ***
</pre>
{% endraw %}
