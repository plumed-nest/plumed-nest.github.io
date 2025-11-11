**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmw9dnm:11986] *** Process received signal ***
[runnervmw9dnm:11986] Signal: Aborted (6)
[runnervmw9dnm:11986] Signal code:  (-6)
[runnervmw9dnm:11986] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2951445330]
[runnervmw9dnm:11986] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f295149eb2c]
[runnervmw9dnm:11986] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f295144527e]
[runnervmw9dnm:11986] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f29514288ff]
[runnervmw9dnm:11986] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f29518a5ff5]
[runnervmw9dnm:11986] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f29518bb0da]
[runnervmw9dnm:11986] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f29518a5a55]
[runnervmw9dnm:11986] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f29518a5a6f]
[runnervmw9dnm:11986] [ 8] plumed(+0x146dd)[0x55a784ae56dd]
[runnervmw9dnm:11986] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f295142a1ca]
[runnervmw9dnm:11986] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f295142a28b]
[runnervmw9dnm:11986] [11] plumed(+0x15365)[0x55a784ae6365]
[runnervmw9dnm:11986] *** End of error message ***
</pre>
{% endraw %}
