**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w14-s4.116/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:10746] *** Process received signal ***
[runnervmmklqx:10746] Signal: Aborted (6)
[runnervmmklqx:10746] Signal code:  (-6)
[runnervmmklqx:10746] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcfa9045330]
[runnervmmklqx:10746] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcfa909eb2c]
[runnervmmklqx:10746] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcfa904527e]
[runnervmmklqx:10746] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcfa90288ff]
[runnervmmklqx:10746] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcfa94a5ff5]
[runnervmmklqx:10746] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcfa94bb0da]
[runnervmmklqx:10746] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcfa94a5a55]
[runnervmmklqx:10746] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcfa94a5a6f]
[runnervmmklqx:10746] [ 8] plumed(+0x146dd)[0x5604ec1ba6dd]
[runnervmmklqx:10746] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcfa902a1ca]
[runnervmmklqx:10746] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcfa902a28b]
[runnervmmklqx:10746] [11] plumed(+0x15365)[0x5604ec1bb365]
[runnervmmklqx:10746] *** End of error message ***
</pre>
{% endraw %}
