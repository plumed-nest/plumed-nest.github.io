**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmi13qx:32363] *** Process received signal ***
[runnervmi13qx:32363] Signal: Aborted (6)
[runnervmi13qx:32363] Signal code:  (-6)
[runnervmi13qx:32363] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ca8445330]
[runnervmi13qx:32363] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ca849eb2c]
[runnervmi13qx:32363] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ca844527e]
[runnervmi13qx:32363] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ca84288ff]
[runnervmi13qx:32363] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ca88a5ff5]
[runnervmi13qx:32363] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ca88bb0da]
[runnervmi13qx:32363] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ca88a5a55]
[runnervmi13qx:32363] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ca88a5a6f]
[runnervmi13qx:32363] [ 8] plumed(+0x146dd)[0x56065659e6dd]
[runnervmi13qx:32363] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ca842a1ca]
[runnervmi13qx:32363] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ca842a28b]
[runnervmi13qx:32363] [11] plumed(+0x15365)[0x56065659f365]
[runnervmi13qx:32363] *** End of error message ***
</pre>
{% endraw %}
