**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmi13qx:32379] *** Process received signal ***
[runnervmi13qx:32379] Signal: Aborted (6)
[runnervmi13qx:32379] Signal code:  (-6)
[runnervmi13qx:32379] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa05d445330]
[runnervmi13qx:32379] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa05d49eb2c]
[runnervmi13qx:32379] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa05d44527e]
[runnervmi13qx:32379] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa05d4288ff]
[runnervmi13qx:32379] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa05d8a5ff5]
[runnervmi13qx:32379] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa05d8bb0da]
[runnervmi13qx:32379] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa05d8a5a55]
[runnervmi13qx:32379] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa05d8a5a6f]
[runnervmi13qx:32379] [ 8] plumed_master(+0x146dd)[0x5577cdd9b6dd]
[runnervmi13qx:32379] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa05d42a1ca]
[runnervmi13qx:32379] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa05d42a28b]
[runnervmi13qx:32379] [11] plumed_master(+0x15365)[0x5577cdd9c365]
[runnervmi13qx:32379] *** End of error message ***
</pre>
{% endraw %}
