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
[runnervmeorf1:05921] *** Process received signal ***
[runnervmeorf1:05921] Signal: Aborted (6)
[runnervmeorf1:05921] Signal code:  (-6)
[runnervmeorf1:05921] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb0ee445330]
[runnervmeorf1:05921] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb0ee49eb2c]
[runnervmeorf1:05921] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb0ee44527e]
[runnervmeorf1:05921] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb0ee4288ff]
[runnervmeorf1:05921] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb0ee8a5ff5]
[runnervmeorf1:05921] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb0ee8bb0da]
[runnervmeorf1:05921] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb0ee8a5a55]
[runnervmeorf1:05921] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb0ee8a5a6f]
[runnervmeorf1:05921] [ 8] plumed_master(+0x146dd)[0x55be046f96dd]
[runnervmeorf1:05921] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb0ee42a1ca]
[runnervmeorf1:05921] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb0ee42a28b]
[runnervmeorf1:05921] [11] plumed_master(+0x15365)[0x55be046fa365]
[runnervmeorf1:05921] *** End of error message ***
</pre>
{% endraw %}
