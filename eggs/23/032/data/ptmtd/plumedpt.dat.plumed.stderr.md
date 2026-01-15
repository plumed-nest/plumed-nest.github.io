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
[runnervmi13qx:32559] *** Process received signal ***
[runnervmi13qx:32559] Signal: Aborted (6)
[runnervmi13qx:32559] Signal code:  (-6)
[runnervmi13qx:32559] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f94efe45330]
[runnervmi13qx:32559] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f94efe9eb2c]
[runnervmi13qx:32559] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f94efe4527e]
[runnervmi13qx:32559] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f94efe288ff]
[runnervmi13qx:32559] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f94f02a5ff5]
[runnervmi13qx:32559] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f94f02bb0da]
[runnervmi13qx:32559] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f94f02a5a55]
[runnervmi13qx:32559] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f94f02a5a6f]
[runnervmi13qx:32559] [ 8] plumed(+0x146dd)[0x5585c05f16dd]
[runnervmi13qx:32559] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f94efe2a1ca]
[runnervmi13qx:32559] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f94efe2a28b]
[runnervmi13qx:32559] [11] plumed(+0x15365)[0x5585c05f2365]
[runnervmi13qx:32559] *** End of error message ***
</pre>
{% endraw %}
