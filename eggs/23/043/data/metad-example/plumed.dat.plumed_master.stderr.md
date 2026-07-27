**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmvrwv9:06083] *** Process received signal ***
[runnervmvrwv9:06083] Signal: Aborted (6)
[runnervmvrwv9:06083] Signal code:  (-6)
[runnervmvrwv9:06083] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f07e7045330]
[runnervmvrwv9:06083] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f07e709eb2c]
[runnervmvrwv9:06083] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f07e704527e]
[runnervmvrwv9:06083] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f07e70288ff]
[runnervmvrwv9:06083] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07e74a5ff5]
[runnervmvrwv9:06083] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07e74bb0da]
[runnervmvrwv9:06083] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07e74a5a55]
[runnervmvrwv9:06083] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07e74a5a6f]
[runnervmvrwv9:06083] [ 8] plumed_master(+0x146dd)[0x55e9d62d66dd]
[runnervmvrwv9:06083] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f07e702a1ca]
[runnervmvrwv9:06083] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f07e702a28b]
[runnervmvrwv9:06083] [11] plumed_master(+0x15365)[0x55e9d62d7365]
[runnervmvrwv9:06083] *** End of error message ***
</pre>
{% endraw %}
