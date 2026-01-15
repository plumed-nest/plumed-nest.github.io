**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w27-s6.924/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:37432] *** Process received signal ***
[runnervmmtnos:37432] Signal: Aborted (6)
[runnervmmtnos:37432] Signal code:  (-6)
[runnervmmtnos:37432] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f83ff645330]
[runnervmmtnos:37432] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f83ff69eb2c]
[runnervmmtnos:37432] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f83ff64527e]
[runnervmmtnos:37432] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83ff6288ff]
[runnervmmtnos:37432] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83ffaa5ff5]
[runnervmmtnos:37432] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83ffabb0da]
[runnervmmtnos:37432] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83ffaa5a55]
[runnervmmtnos:37432] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83ffaa5a6f]
[runnervmmtnos:37432] [ 8] plumed_master(+0x146dd)[0x55e3e7f7f6dd]
[runnervmmtnos:37432] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f83ff62a1ca]
[runnervmmtnos:37432] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f83ff62a28b]
[runnervmmtnos:37432] [11] plumed_master(+0x15365)[0x55e3e7f80365]
[runnervmmtnos:37432] *** End of error message ***
</pre>
{% endraw %}
