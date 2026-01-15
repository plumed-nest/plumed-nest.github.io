**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w15-s4.332/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:36765] *** Process received signal ***
[runnervmmtnos:36765] Signal: Aborted (6)
[runnervmmtnos:36765] Signal code:  (-6)
[runnervmmtnos:36765] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3622845330]
[runnervmmtnos:36765] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f362289eb2c]
[runnervmmtnos:36765] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f362284527e]
[runnervmmtnos:36765] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36228288ff]
[runnervmmtnos:36765] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3622ca5ff5]
[runnervmmtnos:36765] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3622cbb0da]
[runnervmmtnos:36765] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3622ca5a55]
[runnervmmtnos:36765] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3622ca5a6f]
[runnervmmtnos:36765] [ 8] plumed_master(+0x146dd)[0x560ef3a336dd]
[runnervmmtnos:36765] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f362282a1ca]
[runnervmmtnos:36765] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f362282a28b]
[runnervmmtnos:36765] [11] plumed_master(+0x15365)[0x560ef3a34365]
[runnervmmtnos:36765] *** End of error message ***
</pre>
{% endraw %}
