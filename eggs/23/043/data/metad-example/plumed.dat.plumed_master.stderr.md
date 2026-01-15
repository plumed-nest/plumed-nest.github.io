**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmi13qx:34647] *** Process received signal ***
[runnervmi13qx:34647] Signal: Aborted (6)
[runnervmi13qx:34647] Signal code:  (-6)
[runnervmi13qx:34647] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4f39e45330]
[runnervmi13qx:34647] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4f39e9eb2c]
[runnervmi13qx:34647] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4f39e4527e]
[runnervmi13qx:34647] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4f39e288ff]
[runnervmi13qx:34647] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4f3a2a5ff5]
[runnervmi13qx:34647] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4f3a2bb0da]
[runnervmi13qx:34647] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4f3a2a5a55]
[runnervmi13qx:34647] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4f3a2a5a6f]
[runnervmi13qx:34647] [ 8] plumed_master(+0x146dd)[0x560cf5b066dd]
[runnervmi13qx:34647] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4f39e2a1ca]
[runnervmi13qx:34647] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4f39e2a28b]
[runnervmi13qx:34647] [11] plumed_master(+0x15365)[0x560cf5b07365]
[runnervmi13qx:34647] *** End of error message ***
</pre>
{% endraw %}
