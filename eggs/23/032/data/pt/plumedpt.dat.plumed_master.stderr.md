**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmi13qx:32521] *** Process received signal ***
[runnervmi13qx:32521] Signal: Aborted (6)
[runnervmi13qx:32521] Signal code:  (-6)
[runnervmi13qx:32521] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f39fb045330]
[runnervmi13qx:32521] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f39fb09eb2c]
[runnervmi13qx:32521] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f39fb04527e]
[runnervmi13qx:32521] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f39fb0288ff]
[runnervmi13qx:32521] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f39fb4a5ff5]
[runnervmi13qx:32521] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f39fb4bb0da]
[runnervmi13qx:32521] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f39fb4a5a55]
[runnervmi13qx:32521] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f39fb4a5a6f]
[runnervmi13qx:32521] [ 8] plumed_master(+0x146dd)[0x560d2518a6dd]
[runnervmi13qx:32521] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f39fb02a1ca]
[runnervmi13qx:32521] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f39fb02a28b]
[runnervmi13qx:32521] [11] plumed_master(+0x15365)[0x560d2518b365]
[runnervmi13qx:32521] *** End of error message ***
</pre>
{% endraw %}
