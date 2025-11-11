**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:07052] *** Process received signal ***
[runnervmw9dnm:07052] Signal: Aborted (6)
[runnervmw9dnm:07052] Signal code:  (-6)
[runnervmw9dnm:07052] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f310de45330]
[runnervmw9dnm:07052] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f310de9eb2c]
[runnervmw9dnm:07052] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f310de4527e]
[runnervmw9dnm:07052] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f310de288ff]
[runnervmw9dnm:07052] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f310e2a5ff5]
[runnervmw9dnm:07052] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f310e2bb0da]
[runnervmw9dnm:07052] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f310e2a5a55]
[runnervmw9dnm:07052] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f310e2a5a6f]
[runnervmw9dnm:07052] [ 8] plumed_master(+0x146dd)[0x5643e45576dd]
[runnervmw9dnm:07052] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f310de2a1ca]
[runnervmw9dnm:07052] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f310de2a28b]
[runnervmw9dnm:07052] [11] plumed_master(+0x15365)[0x5643e4558365]
[runnervmw9dnm:07052] *** End of error message ***
</pre>
{% endraw %}
