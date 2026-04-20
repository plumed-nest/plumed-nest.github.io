**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w18-s4.980/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:10769] *** Process received signal ***
[runnervmeorf1:10769] Signal: Aborted (6)
[runnervmeorf1:10769] Signal code:  (-6)
[runnervmeorf1:10769] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe3a6845330]
[runnervmeorf1:10769] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe3a689eb2c]
[runnervmeorf1:10769] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe3a684527e]
[runnervmeorf1:10769] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe3a68288ff]
[runnervmeorf1:10769] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe3a6ca5ff5]
[runnervmeorf1:10769] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe3a6cbb0da]
[runnervmeorf1:10769] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe3a6ca5a55]
[runnervmeorf1:10769] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe3a6ca5a6f]
[runnervmeorf1:10769] [ 8] plumed_master(+0x146dd)[0x558ed59536dd]
[runnervmeorf1:10769] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe3a682a1ca]
[runnervmeorf1:10769] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe3a682a28b]
[runnervmeorf1:10769] [11] plumed_master(+0x15365)[0x558ed5954365]
[runnervmeorf1:10769] *** End of error message ***
</pre>
{% endraw %}
