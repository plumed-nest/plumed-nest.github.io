**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w22-s5.844/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:11540] *** Process received signal ***
[runnervmw9dnm:11540] Signal: Aborted (6)
[runnervmw9dnm:11540] Signal code:  (-6)
[runnervmw9dnm:11540] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdf0e245330]
[runnervmw9dnm:11540] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdf0e29eb2c]
[runnervmw9dnm:11540] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdf0e24527e]
[runnervmw9dnm:11540] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdf0e2288ff]
[runnervmw9dnm:11540] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdf0e6a5ff5]
[runnervmw9dnm:11540] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdf0e6bb0da]
[runnervmw9dnm:11540] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdf0e6a5a55]
[runnervmw9dnm:11540] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdf0e6a5a6f]
[runnervmw9dnm:11540] [ 8] plumed_master(+0x146dd)[0x56016c5566dd]
[runnervmw9dnm:11540] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdf0e22a1ca]
[runnervmw9dnm:11540] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdf0e22a28b]
[runnervmw9dnm:11540] [11] plumed_master(+0x15365)[0x56016c557365]
[runnervmw9dnm:11540] *** End of error message ***
</pre>
{% endraw %}
