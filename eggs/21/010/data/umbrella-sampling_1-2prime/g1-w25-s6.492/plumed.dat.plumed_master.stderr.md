**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w25-s6.492/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:37329] *** Process received signal ***
[runnervmmtnos:37329] Signal: Aborted (6)
[runnervmmtnos:37329] Signal code:  (-6)
[runnervmmtnos:37329] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffbcf645330]
[runnervmmtnos:37329] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffbcf69eb2c]
[runnervmmtnos:37329] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffbcf64527e]
[runnervmmtnos:37329] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffbcf6288ff]
[runnervmmtnos:37329] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffbcfaa5ff5]
[runnervmmtnos:37329] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffbcfabb0da]
[runnervmmtnos:37329] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffbcfaa5a55]
[runnervmmtnos:37329] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffbcfaa5a6f]
[runnervmmtnos:37329] [ 8] plumed_master(+0x146dd)[0x5583c2f176dd]
[runnervmmtnos:37329] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffbcf62a1ca]
[runnervmmtnos:37329] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffbcf62a28b]
[runnervmmtnos:37329] [11] plumed_master(+0x15365)[0x5583c2f18365]
[runnervmmtnos:37329] *** End of error message ***
</pre>
{% endraw %}
