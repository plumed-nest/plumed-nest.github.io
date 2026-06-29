**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w10-s3.252/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:10540] *** Process received signal ***
[runnervmmklqx:10540] Signal: Aborted (6)
[runnervmmklqx:10540] Signal code:  (-6)
[runnervmmklqx:10540] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f775e445330]
[runnervmmklqx:10540] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f775e49eb2c]
[runnervmmklqx:10540] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f775e44527e]
[runnervmmklqx:10540] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f775e4288ff]
[runnervmmklqx:10540] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f775e8a5ff5]
[runnervmmklqx:10540] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f775e8bb0da]
[runnervmmklqx:10540] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f775e8a5a55]
[runnervmmklqx:10540] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f775e8a5a6f]
[runnervmmklqx:10540] [ 8] plumed(+0x146dd)[0x55fce49c96dd]
[runnervmmklqx:10540] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f775e42a1ca]
[runnervmmklqx:10540] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f775e42a28b]
[runnervmmklqx:10540] [11] plumed(+0x15365)[0x55fce49ca365]
[runnervmmklqx:10540] *** End of error message ***
</pre>
{% endraw %}
