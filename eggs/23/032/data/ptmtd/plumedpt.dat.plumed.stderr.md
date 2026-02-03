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
[runnervmkj6or:05472] *** Process received signal ***
[runnervmkj6or:05472] Signal: Aborted (6)
[runnervmkj6or:05472] Signal code:  (-6)
[runnervmkj6or:05472] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23c7a45330]
[runnervmkj6or:05472] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23c7a9eb2c]
[runnervmkj6or:05472] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23c7a4527e]
[runnervmkj6or:05472] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23c7a288ff]
[runnervmkj6or:05472] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23c7ea5ff5]
[runnervmkj6or:05472] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23c7ebb0da]
[runnervmkj6or:05472] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23c7ea5a55]
[runnervmkj6or:05472] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23c7ea5a6f]
[runnervmkj6or:05472] [ 8] plumed(+0x146dd)[0x556faee0c6dd]
[runnervmkj6or:05472] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23c7a2a1ca]
[runnervmkj6or:05472] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23c7a2a28b]
[runnervmkj6or:05472] [11] plumed(+0x15365)[0x556faee0d365]
[runnervmkj6or:05472] *** End of error message ***
</pre>
{% endraw %}
