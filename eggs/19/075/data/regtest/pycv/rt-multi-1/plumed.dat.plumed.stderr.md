**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmw9dnm:12037] *** Process received signal ***
[runnervmw9dnm:12037] Signal: Aborted (6)
[runnervmw9dnm:12037] Signal code:  (-6)
[runnervmw9dnm:12037] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd1d8a45330]
[runnervmw9dnm:12037] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd1d8a9eb2c]
[runnervmw9dnm:12037] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd1d8a4527e]
[runnervmw9dnm:12037] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd1d8a288ff]
[runnervmw9dnm:12037] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd1d8ea5ff5]
[runnervmw9dnm:12037] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd1d8ebb0da]
[runnervmw9dnm:12037] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd1d8ea5a55]
[runnervmw9dnm:12037] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd1d8ea5a6f]
[runnervmw9dnm:12037] [ 8] plumed(+0x146dd)[0x5649c8e466dd]
[runnervmw9dnm:12037] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd1d8a2a1ca]
[runnervmw9dnm:12037] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd1d8a2a28b]
[runnervmw9dnm:12037] [11] plumed(+0x15365)[0x5649c8e47365]
[runnervmw9dnm:12037] *** End of error message ***
</pre>
{% endraw %}
