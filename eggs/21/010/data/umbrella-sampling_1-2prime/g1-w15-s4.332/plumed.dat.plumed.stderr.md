**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w15-s4.332/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmvrwv9:06667] *** Process received signal ***
[runnervmvrwv9:06667] Signal: Aborted (6)
[runnervmvrwv9:06667] Signal code:  (-6)
[runnervmvrwv9:06667] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f94d4245330]
[runnervmvrwv9:06667] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f94d429eb2c]
[runnervmvrwv9:06667] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f94d424527e]
[runnervmvrwv9:06667] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f94d42288ff]
[runnervmvrwv9:06667] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f94d46a5ff5]
[runnervmvrwv9:06667] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f94d46bb0da]
[runnervmvrwv9:06667] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f94d46a5a55]
[runnervmvrwv9:06667] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f94d46a5a6f]
[runnervmvrwv9:06667] [ 8] plumed(+0x146dd)[0x5592709806dd]
[runnervmvrwv9:06667] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f94d422a1ca]
[runnervmvrwv9:06667] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f94d422a28b]
[runnervmvrwv9:06667] [11] plumed(+0x15365)[0x559270981365]
[runnervmvrwv9:06667] *** End of error message ***
</pre>
{% endraw %}
