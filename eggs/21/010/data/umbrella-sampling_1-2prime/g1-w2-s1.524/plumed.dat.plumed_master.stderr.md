**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w2-s1.524/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:10872] *** Process received signal ***
[runnervmeorf1:10872] Signal: Aborted (6)
[runnervmeorf1:10872] Signal code:  (-6)
[runnervmeorf1:10872] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0bcb045330]
[runnervmeorf1:10872] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0bcb09eb2c]
[runnervmeorf1:10872] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0bcb04527e]
[runnervmeorf1:10872] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0bcb0288ff]
[runnervmeorf1:10872] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0bcb4a5ff5]
[runnervmeorf1:10872] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0bcb4bb0da]
[runnervmeorf1:10872] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0bcb4a5a55]
[runnervmeorf1:10872] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0bcb4a5a6f]
[runnervmeorf1:10872] [ 8] plumed_master(+0x146dd)[0x5595d552d6dd]
[runnervmeorf1:10872] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0bcb02a1ca]
[runnervmeorf1:10872] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0bcb02a28b]
[runnervmeorf1:10872] [11] plumed_master(+0x15365)[0x5595d552e365]
[runnervmeorf1:10872] *** End of error message ***
</pre>
{% endraw %}
