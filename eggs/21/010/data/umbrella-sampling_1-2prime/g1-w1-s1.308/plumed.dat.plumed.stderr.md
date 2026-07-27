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
[runnervmvrwv9:06357] *** Process received signal ***
[runnervmvrwv9:06357] Signal: Aborted (6)
[runnervmvrwv9:06357] Signal code:  (-6)
[runnervmvrwv9:06357] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1803e45330]
[runnervmvrwv9:06357] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1803e9eb2c]
[runnervmvrwv9:06357] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1803e4527e]
[runnervmvrwv9:06357] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1803e288ff]
[runnervmvrwv9:06357] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f18042a5ff5]
[runnervmvrwv9:06357] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f18042bb0da]
[runnervmvrwv9:06357] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f18042a5a55]
[runnervmvrwv9:06357] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f18042a5a6f]
[runnervmvrwv9:06357] [ 8] plumed(+0x146dd)[0x55bbcf83c6dd]
[runnervmvrwv9:06357] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1803e2a1ca]
[runnervmvrwv9:06357] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1803e2a28b]
[runnervmvrwv9:06357] [11] plumed(+0x15365)[0x55bbcf83d365]
[runnervmvrwv9:06357] *** End of error message ***
</pre>
{% endraw %}
