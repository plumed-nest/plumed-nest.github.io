**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w15-s4.332/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:10598] *** Process received signal ***
[runnervmeorf1:10598] Signal: Aborted (6)
[runnervmeorf1:10598] Signal code:  (-6)
[runnervmeorf1:10598] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6272a45330]
[runnervmeorf1:10598] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6272a9eb2c]
[runnervmeorf1:10598] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6272a4527e]
[runnervmeorf1:10598] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6272a288ff]
[runnervmeorf1:10598] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6272ea5ff5]
[runnervmeorf1:10598] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6272ebb0da]
[runnervmeorf1:10598] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6272ea5a55]
[runnervmeorf1:10598] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6272ea5a6f]
[runnervmeorf1:10598] [ 8] plumed(+0x146dd)[0x564dbd8a56dd]
[runnervmeorf1:10598] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6272a2a1ca]
[runnervmeorf1:10598] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6272a2a28b]
[runnervmeorf1:10598] [11] plumed(+0x15365)[0x564dbd8a6365]
[runnervmeorf1:10598] *** End of error message ***
</pre>
{% endraw %}
