**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
Download: [zipped raw stdout](plumed_FM.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FM.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "FPS" is not known.
[runnervmeorf1:11482] *** Process received signal ***
[runnervmeorf1:11482] Signal: Aborted (6)
[runnervmeorf1:11482] Signal code:  (-6)
[runnervmeorf1:11482] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f630d045330]
[runnervmeorf1:11482] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f630d09eb2c]
[runnervmeorf1:11482] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f630d04527e]
[runnervmeorf1:11482] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f630d0288ff]
[runnervmeorf1:11482] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f630d4a5ff5]
[runnervmeorf1:11482] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f630d4bb0da]
[runnervmeorf1:11482] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f630d4a5a55]
[runnervmeorf1:11482] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f630d4a5a6f]
[runnervmeorf1:11482] [ 8] plumed(+0x146dd)[0x563283b6b6dd]
[runnervmeorf1:11482] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f630d02a1ca]
[runnervmeorf1:11482] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f630d02a28b]
[runnervmeorf1:11482] [11] plumed(+0x15365)[0x563283b6c365]
[runnervmeorf1:11482] *** End of error message ***
</pre>
{% endraw %}
