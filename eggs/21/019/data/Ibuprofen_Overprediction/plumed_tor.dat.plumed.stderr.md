**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervmi13qx:40044] *** Process received signal ***
[runnervmi13qx:40044] Signal: Aborted (6)
[runnervmi13qx:40044] Signal code:  (-6)
[runnervmi13qx:40044] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f095f245330]
[runnervmi13qx:40044] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f095f29eb2c]
[runnervmi13qx:40044] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f095f24527e]
[runnervmi13qx:40044] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f095f2288ff]
[runnervmi13qx:40044] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f095f6a5ff5]
[runnervmi13qx:40044] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f095f6bb0da]
[runnervmi13qx:40044] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f095f6a5a55]
[runnervmi13qx:40044] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f095f6a5a6f]
[runnervmi13qx:40044] [ 8] plumed(+0x146dd)[0x55eb56ac56dd]
[runnervmi13qx:40044] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f095f22a1ca]
[runnervmi13qx:40044] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f095f22a28b]
[runnervmi13qx:40044] [11] plumed(+0x15365)[0x55eb56ac6365]
[runnervmi13qx:40044] *** End of error message ***
</pre>
{% endraw %}
