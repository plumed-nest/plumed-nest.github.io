**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:06984] *** Process received signal ***
[runnervmw9dnm:06984] Signal: Aborted (6)
[runnervmw9dnm:06984] Signal code:  (-6)
[runnervmw9dnm:06984] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff5d1245330]
[runnervmw9dnm:06984] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff5d129eb2c]
[runnervmw9dnm:06984] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff5d124527e]
[runnervmw9dnm:06984] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5d12288ff]
[runnervmw9dnm:06984] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5d16a5ff5]
[runnervmw9dnm:06984] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5d16bb0da]
[runnervmw9dnm:06984] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5d16a5a55]
[runnervmw9dnm:06984] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5d16a5a6f]
[runnervmw9dnm:06984] [ 8] plumed(+0x146dd)[0x557f2e8506dd]
[runnervmw9dnm:06984] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff5d122a1ca]
[runnervmw9dnm:06984] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff5d122a28b]
[runnervmw9dnm:06984] [11] plumed(+0x15365)[0x557f2e851365]
[runnervmw9dnm:06984] *** End of error message ***
</pre>
{% endraw %}
