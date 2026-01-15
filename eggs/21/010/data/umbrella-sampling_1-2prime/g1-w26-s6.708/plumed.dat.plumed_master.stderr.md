**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w26-s6.708/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:37380] *** Process received signal ***
[runnervmmtnos:37380] Signal: Aborted (6)
[runnervmmtnos:37380] Signal code:  (-6)
[runnervmmtnos:37380] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5ced245330]
[runnervmmtnos:37380] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5ced29eb2c]
[runnervmmtnos:37380] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5ced24527e]
[runnervmmtnos:37380] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5ced2288ff]
[runnervmmtnos:37380] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5ced6a5ff5]
[runnervmmtnos:37380] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5ced6bb0da]
[runnervmmtnos:37380] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5ced6a5a55]
[runnervmmtnos:37380] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5ced6a5a6f]
[runnervmmtnos:37380] [ 8] plumed_master(+0x146dd)[0x55b5ef8f76dd]
[runnervmmtnos:37380] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5ced22a1ca]
[runnervmmtnos:37380] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5ced22a28b]
[runnervmmtnos:37380] [11] plumed_master(+0x15365)[0x55b5ef8f8365]
[runnervmmtnos:37380] *** End of error message ***
</pre>
{% endraw %}
