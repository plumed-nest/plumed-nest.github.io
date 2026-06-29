**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w1-s1.308/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:10487] *** Process received signal ***
[runnervmmklqx:10487] Signal: Aborted (6)
[runnervmmklqx:10487] Signal code:  (-6)
[runnervmmklqx:10487] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faf44a45330]
[runnervmmklqx:10487] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faf44a9eb2c]
[runnervmmklqx:10487] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faf44a4527e]
[runnervmmklqx:10487] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faf44a288ff]
[runnervmmklqx:10487] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faf44ea5ff5]
[runnervmmklqx:10487] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faf44ebb0da]
[runnervmmklqx:10487] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faf44ea5a55]
[runnervmmklqx:10487] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faf44ea5a6f]
[runnervmmklqx:10487] [ 8] plumed(+0x146dd)[0x564fba3c76dd]
[runnervmmklqx:10487] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faf44a2a1ca]
[runnervmmklqx:10487] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faf44a2a28b]
[runnervmmklqx:10487] [11] plumed(+0x15365)[0x564fba3c8365]
[runnervmmklqx:10487] *** End of error message ***
</pre>
{% endraw %}
