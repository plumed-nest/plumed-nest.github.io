**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w26-s6.708/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:11428] *** Process received signal ***
[runnervmmklqx:11428] Signal: Aborted (6)
[runnervmmklqx:11428] Signal code:  (-6)
[runnervmmklqx:11428] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6ed0445330]
[runnervmmklqx:11428] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6ed049eb2c]
[runnervmmklqx:11428] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6ed044527e]
[runnervmmklqx:11428] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6ed04288ff]
[runnervmmklqx:11428] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6ed08a5ff5]
[runnervmmklqx:11428] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6ed08bb0da]
[runnervmmklqx:11428] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6ed08a5a55]
[runnervmmklqx:11428] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6ed08a5a6f]
[runnervmmklqx:11428] [ 8] plumed_master(+0x146dd)[0x564ada4d26dd]
[runnervmmklqx:11428] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6ed042a1ca]
[runnervmmklqx:11428] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6ed042a28b]
[runnervmmklqx:11428] [11] plumed_master(+0x15365)[0x564ada4d3365]
[runnervmmklqx:11428] *** End of error message ***
</pre>
{% endraw %}
