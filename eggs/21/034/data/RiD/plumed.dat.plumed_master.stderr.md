**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervmi13qx:36408] *** Process received signal ***
[runnervmi13qx:36408] Signal: Aborted (6)
[runnervmi13qx:36408] Signal code:  (-6)
[runnervmi13qx:36408] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdbea645330]
[runnervmi13qx:36408] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdbea69eb2c]
[runnervmi13qx:36408] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdbea64527e]
[runnervmi13qx:36408] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdbea6288ff]
[runnervmi13qx:36408] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdbeaaa5ff5]
[runnervmi13qx:36408] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdbeaabb0da]
[runnervmi13qx:36408] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdbeaaa5a55]
[runnervmi13qx:36408] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdbeaaa5a6f]
[runnervmi13qx:36408] [ 8] plumed_master(+0x146dd)[0x560caf3596dd]
[runnervmi13qx:36408] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdbea62a1ca]
[runnervmi13qx:36408] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdbea62a28b]
[runnervmi13qx:36408] [11] plumed_master(+0x15365)[0x560caf35a365]
[runnervmi13qx:36408] *** End of error message ***
</pre>
{% endraw %}
