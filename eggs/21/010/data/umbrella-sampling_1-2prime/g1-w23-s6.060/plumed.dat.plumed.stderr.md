**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:11259] *** Process received signal ***
[runnervmmklqx:11259] Signal: Aborted (6)
[runnervmmklqx:11259] Signal code:  (-6)
[runnervmmklqx:11259] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb2b7245330]
[runnervmmklqx:11259] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb2b729eb2c]
[runnervmmklqx:11259] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb2b724527e]
[runnervmmklqx:11259] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb2b72288ff]
[runnervmmklqx:11259] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb2b76a5ff5]
[runnervmmklqx:11259] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb2b76bb0da]
[runnervmmklqx:11259] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb2b76a5a55]
[runnervmmklqx:11259] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb2b76a5a6f]
[runnervmmklqx:11259] [ 8] plumed(+0x146dd)[0x562ac68446dd]
[runnervmmklqx:11259] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb2b722a1ca]
[runnervmmklqx:11259] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb2b722a28b]
[runnervmmklqx:11259] [11] plumed(+0x15365)[0x562ac6845365]
[runnervmmklqx:11259] *** End of error message ***
</pre>
{% endraw %}
