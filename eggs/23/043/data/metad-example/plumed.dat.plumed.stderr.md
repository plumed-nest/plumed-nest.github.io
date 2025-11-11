**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmw9dnm:07639] *** Process received signal ***
[runnervmw9dnm:07639] Signal: Aborted (6)
[runnervmw9dnm:07639] Signal code:  (-6)
[runnervmw9dnm:07639] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdce0445330]
[runnervmw9dnm:07639] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdce049eb2c]
[runnervmw9dnm:07639] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdce044527e]
[runnervmw9dnm:07639] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdce04288ff]
[runnervmw9dnm:07639] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdce08a5ff5]
[runnervmw9dnm:07639] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdce08bb0da]
[runnervmw9dnm:07639] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdce08a5a55]
[runnervmw9dnm:07639] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdce08a5a6f]
[runnervmw9dnm:07639] [ 8] plumed(+0x146dd)[0x55b0fe2186dd]
[runnervmw9dnm:07639] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdce042a1ca]
[runnervmw9dnm:07639] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdce042a28b]
[runnervmw9dnm:07639] [11] plumed(+0x15365)[0x55b0fe219365]
[runnervmw9dnm:07639] *** End of error message ***
</pre>
{% endraw %}
