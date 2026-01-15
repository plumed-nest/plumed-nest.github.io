**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervmi13qx:40060] *** Process received signal ***
[runnervmi13qx:40060] Signal: Aborted (6)
[runnervmi13qx:40060] Signal code:  (-6)
[runnervmi13qx:40060] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d9b245330]
[runnervmi13qx:40060] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d9b29eb2c]
[runnervmi13qx:40060] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d9b24527e]
[runnervmi13qx:40060] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d9b2288ff]
[runnervmi13qx:40060] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d9b6a5ff5]
[runnervmi13qx:40060] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d9b6bb0da]
[runnervmi13qx:40060] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d9b6a5a55]
[runnervmi13qx:40060] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d9b6a5a6f]
[runnervmi13qx:40060] [ 8] plumed_master(+0x146dd)[0x562dd96f16dd]
[runnervmi13qx:40060] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d9b22a1ca]
[runnervmi13qx:40060] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d9b22a28b]
[runnervmi13qx:40060] [11] plumed_master(+0x15365)[0x562dd96f2365]
[runnervmi13qx:40060] *** End of error message ***
</pre>
{% endraw %}
