**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w25-s6.492/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:11361] *** Process received signal ***
[runnervmmklqx:11361] Signal: Aborted (6)
[runnervmmklqx:11361] Signal code:  (-6)
[runnervmmklqx:11361] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0496645330]
[runnervmmklqx:11361] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f049669eb2c]
[runnervmmklqx:11361] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f049664527e]
[runnervmmklqx:11361] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f04966288ff]
[runnervmmklqx:11361] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0496aa5ff5]
[runnervmmklqx:11361] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0496abb0da]
[runnervmmklqx:11361] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0496aa5a55]
[runnervmmklqx:11361] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0496aa5a6f]
[runnervmmklqx:11361] [ 8] plumed(+0x146dd)[0x555f431d56dd]
[runnervmmklqx:11361] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f049662a1ca]
[runnervmmklqx:11361] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f049662a28b]
[runnervmmklqx:11361] [11] plumed(+0x15365)[0x555f431d6365]
[runnervmmklqx:11361] *** End of error message ***
</pre>
{% endraw %}
