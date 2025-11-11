**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w25-s6.492/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:11678] *** Process received signal ***
[runnervmw9dnm:11678] Signal: Aborted (6)
[runnervmw9dnm:11678] Signal code:  (-6)
[runnervmw9dnm:11678] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3846845330]
[runnervmw9dnm:11678] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f384689eb2c]
[runnervmw9dnm:11678] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f384684527e]
[runnervmw9dnm:11678] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f38468288ff]
[runnervmw9dnm:11678] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3846ca5ff5]
[runnervmw9dnm:11678] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3846cbb0da]
[runnervmw9dnm:11678] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3846ca5a55]
[runnervmw9dnm:11678] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3846ca5a6f]
[runnervmw9dnm:11678] [ 8] plumed(+0x146dd)[0x55b79ad446dd]
[runnervmw9dnm:11678] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f384682a1ca]
[runnervmw9dnm:11678] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f384682a28b]
[runnervmw9dnm:11678] [11] plumed(+0x15365)[0x55b79ad45365]
[runnervmw9dnm:11678] *** End of error message ***
</pre>
{% endraw %}
