**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w2-s1.524/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:37008] *** Process received signal ***
[runnervmmtnos:37008] Signal: Aborted (6)
[runnervmmtnos:37008] Signal code:  (-6)
[runnervmmtnos:37008] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab75c45330]
[runnervmmtnos:37008] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab75c9eb2c]
[runnervmmtnos:37008] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab75c4527e]
[runnervmmtnos:37008] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab75c288ff]
[runnervmmtnos:37008] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab760a5ff5]
[runnervmmtnos:37008] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab760bb0da]
[runnervmmtnos:37008] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab760a5a55]
[runnervmmtnos:37008] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab760a5a6f]
[runnervmmtnos:37008] [ 8] plumed(+0x146dd)[0x56271cf4e6dd]
[runnervmmtnos:37008] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab75c2a1ca]
[runnervmmtnos:37008] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab75c2a28b]
[runnervmmtnos:37008] [11] plumed(+0x15365)[0x56271cf4f365]
[runnervmmtnos:37008] *** End of error message ***
</pre>
{% endraw %}
