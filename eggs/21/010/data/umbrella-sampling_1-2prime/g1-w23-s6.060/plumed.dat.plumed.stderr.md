**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:37212] *** Process received signal ***
[runnervmmtnos:37212] Signal: Aborted (6)
[runnervmmtnos:37212] Signal code:  (-6)
[runnervmmtnos:37212] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdde8245330]
[runnervmmtnos:37212] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdde829eb2c]
[runnervmmtnos:37212] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdde824527e]
[runnervmmtnos:37212] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdde82288ff]
[runnervmmtnos:37212] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdde86a5ff5]
[runnervmmtnos:37212] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdde86bb0da]
[runnervmmtnos:37212] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdde86a5a55]
[runnervmmtnos:37212] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdde86a5a6f]
[runnervmmtnos:37212] [ 8] plumed(+0x146dd)[0x5643b62686dd]
[runnervmmtnos:37212] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdde822a1ca]
[runnervmmtnos:37212] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdde822a28b]
[runnervmmtnos:37212] [11] plumed(+0x15365)[0x5643b6269365]
[runnervmmtnos:37212] *** End of error message ***
</pre>
{% endraw %}
