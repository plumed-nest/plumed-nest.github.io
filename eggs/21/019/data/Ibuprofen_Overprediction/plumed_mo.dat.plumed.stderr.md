**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[runnervmw9dnm:13019] *** Process received signal ***
[runnervmw9dnm:13019] Signal: Aborted (6)
[runnervmw9dnm:13019] Signal code:  (-6)
[runnervmw9dnm:13019] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad69c45330]
[runnervmw9dnm:13019] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad69c9eb2c]
[runnervmw9dnm:13019] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad69c4527e]
[runnervmw9dnm:13019] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad69c288ff]
[runnervmw9dnm:13019] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad6a0a5ff5]
[runnervmw9dnm:13019] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad6a0bb0da]
[runnervmw9dnm:13019] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad6a0a5a55]
[runnervmw9dnm:13019] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad6a0a5a6f]
[runnervmw9dnm:13019] [ 8] plumed(+0x146dd)[0x55ee5eaf46dd]
[runnervmw9dnm:13019] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad69c2a1ca]
[runnervmw9dnm:13019] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad69c2a28b]
[runnervmw9dnm:13019] [11] plumed(+0x15365)[0x55ee5eaf5365]
[runnervmw9dnm:13019] *** End of error message ***
</pre>
{% endraw %}
