**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmeorf1:05903] *** Process received signal ***
[runnervmeorf1:05903] Signal: Aborted (6)
[runnervmeorf1:05903] Signal code:  (-6)
[runnervmeorf1:05903] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0c99445330]
[runnervmeorf1:05903] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0c9949eb2c]
[runnervmeorf1:05903] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0c9944527e]
[runnervmeorf1:05903] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0c994288ff]
[runnervmeorf1:05903] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0c998a5ff5]
[runnervmeorf1:05903] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0c998bb0da]
[runnervmeorf1:05903] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0c998a5a55]
[runnervmeorf1:05903] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0c998a5a6f]
[runnervmeorf1:05903] [ 8] plumed(+0x146dd)[0x55961b8da6dd]
[runnervmeorf1:05903] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0c9942a1ca]
[runnervmeorf1:05903] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0c9942a28b]
[runnervmeorf1:05903] [11] plumed(+0x15365)[0x55961b8db365]
[runnervmeorf1:05903] *** End of error message ***
</pre>
{% endraw %}
