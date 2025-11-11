**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:06843] *** Process received signal ***
[runnervmw9dnm:06843] Signal: Aborted (6)
[runnervmw9dnm:06843] Signal code:  (-6)
[runnervmw9dnm:06843] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f467c045330]
[runnervmw9dnm:06843] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f467c09eb2c]
[runnervmw9dnm:06843] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f467c04527e]
[runnervmw9dnm:06843] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f467c0288ff]
[runnervmw9dnm:06843] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f467c4a5ff5]
[runnervmw9dnm:06843] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f467c4bb0da]
[runnervmw9dnm:06843] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f467c4a5a55]
[runnervmw9dnm:06843] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f467c4a5a6f]
[runnervmw9dnm:06843] [ 8] plumed_master(+0x146dd)[0x558f89f246dd]
[runnervmw9dnm:06843] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f467c02a1ca]
[runnervmw9dnm:06843] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f467c02a28b]
[runnervmw9dnm:06843] [11] plumed_master(+0x15365)[0x558f89f25365]
[runnervmw9dnm:06843] *** End of error message ***
</pre>
{% endraw %}
