**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w2-s1.524/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:11054] *** Process received signal ***
[runnervmmklqx:11054] Signal: Aborted (6)
[runnervmmklqx:11054] Signal code:  (-6)
[runnervmmklqx:11054] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f072c645330]
[runnervmmklqx:11054] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f072c69eb2c]
[runnervmmklqx:11054] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f072c64527e]
[runnervmmklqx:11054] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f072c6288ff]
[runnervmmklqx:11054] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f072caa5ff5]
[runnervmmklqx:11054] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f072cabb0da]
[runnervmmklqx:11054] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f072caa5a55]
[runnervmmklqx:11054] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f072caa5a6f]
[runnervmmklqx:11054] [ 8] plumed(+0x146dd)[0x55e2167876dd]
[runnervmmklqx:11054] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f072c62a1ca]
[runnervmmklqx:11054] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f072c62a28b]
[runnervmmklqx:11054] [11] plumed(+0x15365)[0x55e216788365]
[runnervmmklqx:11054] *** End of error message ***
</pre>
{% endraw %}
