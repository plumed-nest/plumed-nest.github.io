**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmmklqx:05358] *** Process received signal ***
[runnervmmklqx:05358] Signal: Aborted (6)
[runnervmmklqx:05358] Signal code:  (-6)
[runnervmmklqx:05358] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f340b445330]
[runnervmmklqx:05358] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f340b49eb2c]
[runnervmmklqx:05358] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f340b44527e]
[runnervmmklqx:05358] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f340b4288ff]
[runnervmmklqx:05358] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f340b8a5ff5]
[runnervmmklqx:05358] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f340b8bb0da]
[runnervmmklqx:05358] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f340b8a5a55]
[runnervmmklqx:05358] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f340b8a5a6f]
[runnervmmklqx:05358] [ 8] plumed(+0x146dd)[0x55c7c281f6dd]
[runnervmmklqx:05358] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f340b42a1ca]
[runnervmmklqx:05358] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f340b42a28b]
[runnervmmklqx:05358] [11] plumed(+0x15365)[0x55c7c2820365]
[runnervmmklqx:05358] *** End of error message ***
</pre>
{% endraw %}
