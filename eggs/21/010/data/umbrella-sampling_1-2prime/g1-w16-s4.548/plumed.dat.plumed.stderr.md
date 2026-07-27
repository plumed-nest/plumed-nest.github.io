**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w16-s4.548/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmvrwv9:06719] *** Process received signal ***
[runnervmvrwv9:06719] Signal: Aborted (6)
[runnervmvrwv9:06719] Signal code:  (-6)
[runnervmvrwv9:06719] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f68e0c45330]
[runnervmvrwv9:06719] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f68e0c9eb2c]
[runnervmvrwv9:06719] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f68e0c4527e]
[runnervmvrwv9:06719] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68e0c288ff]
[runnervmvrwv9:06719] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68e10a5ff5]
[runnervmvrwv9:06719] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68e10bb0da]
[runnervmvrwv9:06719] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68e10a5a55]
[runnervmvrwv9:06719] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68e10a5a6f]
[runnervmvrwv9:06719] [ 8] plumed(+0x146dd)[0x55cd2d79a6dd]
[runnervmvrwv9:06719] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f68e0c2a1ca]
[runnervmvrwv9:06719] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f68e0c2a28b]
[runnervmvrwv9:06719] [11] plumed(+0x15365)[0x55cd2d79b365]
[runnervmvrwv9:06719] *** End of error message ***
</pre>
{% endraw %}
