**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w17-s4.764/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:36851] *** Process received signal ***
[runnervmmtnos:36851] Signal: Aborted (6)
[runnervmmtnos:36851] Signal code:  (-6)
[runnervmmtnos:36851] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd76f445330]
[runnervmmtnos:36851] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd76f49eb2c]
[runnervmmtnos:36851] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd76f44527e]
[runnervmmtnos:36851] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd76f4288ff]
[runnervmmtnos:36851] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd76f8a5ff5]
[runnervmmtnos:36851] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd76f8bb0da]
[runnervmmtnos:36851] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd76f8a5a55]
[runnervmmtnos:36851] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd76f8a5a6f]
[runnervmmtnos:36851] [ 8] plumed(+0x146dd)[0x560afe7fe6dd]
[runnervmmtnos:36851] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd76f42a1ca]
[runnervmmtnos:36851] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd76f42a28b]
[runnervmmtnos:36851] [11] plumed(+0x15365)[0x560afe7ff365]
[runnervmmtnos:36851] *** End of error message ***
</pre>
{% endraw %}
