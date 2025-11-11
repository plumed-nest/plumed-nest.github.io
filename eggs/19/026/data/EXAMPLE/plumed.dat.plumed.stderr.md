**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervmw9dnm:11792] *** Process received signal ***
[runnervmw9dnm:11792] Signal: Aborted (6)
[runnervmw9dnm:11792] Signal code:  (-6)
[runnervmw9dnm:11792] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe507645330]
[runnervmw9dnm:11792] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe50769eb2c]
[runnervmw9dnm:11792] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe50764527e]
[runnervmw9dnm:11792] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5076288ff]
[runnervmw9dnm:11792] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe507aa5ff5]
[runnervmw9dnm:11792] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe507abb0da]
[runnervmw9dnm:11792] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe507aa5a55]
[runnervmw9dnm:11792] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe507aa5a6f]
[runnervmw9dnm:11792] [ 8] plumed(+0x146dd)[0x55764760c6dd]
[runnervmw9dnm:11792] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe50762a1ca]
[runnervmw9dnm:11792] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe50762a28b]
[runnervmw9dnm:11792] [11] plumed(+0x15365)[0x55764760d365]
[runnervmw9dnm:11792] *** End of error message ***
</pre>
{% endraw %}
