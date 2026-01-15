**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmi13qx:32575] *** Process received signal ***
[runnervmi13qx:32575] Signal: Aborted (6)
[runnervmi13qx:32575] Signal code:  (-6)
[runnervmi13qx:32575] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f243d045330]
[runnervmi13qx:32575] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f243d09eb2c]
[runnervmi13qx:32575] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f243d04527e]
[runnervmi13qx:32575] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f243d0288ff]
[runnervmi13qx:32575] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f243d4a5ff5]
[runnervmi13qx:32575] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f243d4bb0da]
[runnervmi13qx:32575] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f243d4a5a55]
[runnervmi13qx:32575] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f243d4a5a6f]
[runnervmi13qx:32575] [ 8] plumed_master(+0x146dd)[0x5596c28866dd]
[runnervmi13qx:32575] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f243d02a1ca]
[runnervmi13qx:32575] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f243d02a28b]
[runnervmi13qx:32575] [11] plumed_master(+0x15365)[0x5596c2887365]
[runnervmi13qx:32575] *** End of error message ***
</pre>
{% endraw %}
