**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:37227] *** Process received signal ***
[runnervmmtnos:37227] Signal: Aborted (6)
[runnervmmtnos:37227] Signal code:  (-6)
[runnervmmtnos:37227] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc570645330]
[runnervmmtnos:37227] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc57069eb2c]
[runnervmmtnos:37227] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc57064527e]
[runnervmmtnos:37227] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc5706288ff]
[runnervmmtnos:37227] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc570aa5ff5]
[runnervmmtnos:37227] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc570abb0da]
[runnervmmtnos:37227] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc570aa5a55]
[runnervmmtnos:37227] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc570aa5a6f]
[runnervmmtnos:37227] [ 8] plumed_master(+0x146dd)[0x55ab2eba96dd]
[runnervmmtnos:37227] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc57062a1ca]
[runnervmmtnos:37227] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc57062a28b]
[runnervmmtnos:37227] [11] plumed_master(+0x15365)[0x55ab2ebaa365]
[runnervmmtnos:37227] *** End of error message ***
</pre>
{% endraw %}
