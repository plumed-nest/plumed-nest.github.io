**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:06826] *** Process received signal ***
[runnervmw9dnm:06826] Signal: Aborted (6)
[runnervmw9dnm:06826] Signal code:  (-6)
[runnervmw9dnm:06826] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6313245330]
[runnervmw9dnm:06826] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f631329eb2c]
[runnervmw9dnm:06826] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f631324527e]
[runnervmw9dnm:06826] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f63132288ff]
[runnervmw9dnm:06826] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63136a5ff5]
[runnervmw9dnm:06826] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63136bb0da]
[runnervmw9dnm:06826] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63136a5a55]
[runnervmw9dnm:06826] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63136a5a6f]
[runnervmw9dnm:06826] [ 8] plumed(+0x146dd)[0x563c56aa96dd]
[runnervmw9dnm:06826] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f631322a1ca]
[runnervmw9dnm:06826] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f631322a28b]
[runnervmw9dnm:06826] [11] plumed(+0x15365)[0x563c56aaa365]
[runnervmw9dnm:06826] *** End of error message ***
</pre>
{% endraw %}
