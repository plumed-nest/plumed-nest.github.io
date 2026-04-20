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
[runnervmeorf1:11263] *** Process received signal ***
[runnervmeorf1:11263] Signal: Aborted (6)
[runnervmeorf1:11263] Signal code:  (-6)
[runnervmeorf1:11263] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4140445330]
[runnervmeorf1:11263] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f414049eb2c]
[runnervmeorf1:11263] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f414044527e]
[runnervmeorf1:11263] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f41404288ff]
[runnervmeorf1:11263] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41408a5ff5]
[runnervmeorf1:11263] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41408bb0da]
[runnervmeorf1:11263] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41408a5a55]
[runnervmeorf1:11263] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41408a5a6f]
[runnervmeorf1:11263] [ 8] plumed_master(+0x146dd)[0x55801d9356dd]
[runnervmeorf1:11263] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f414042a1ca]
[runnervmeorf1:11263] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f414042a28b]
[runnervmeorf1:11263] [11] plumed_master(+0x15365)[0x55801d936365]
[runnervmeorf1:11263] *** End of error message ***
</pre>
{% endraw %}
