**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervmi13qx:36393] *** Process received signal ***
[runnervmi13qx:36393] Signal: Aborted (6)
[runnervmi13qx:36393] Signal code:  (-6)
[runnervmi13qx:36393] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbef8445330]
[runnervmi13qx:36393] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbef849eb2c]
[runnervmi13qx:36393] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbef844527e]
[runnervmi13qx:36393] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbef84288ff]
[runnervmi13qx:36393] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbef88a5ff5]
[runnervmi13qx:36393] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbef88bb0da]
[runnervmi13qx:36393] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbef88a5a55]
[runnervmi13qx:36393] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbef88a5a6f]
[runnervmi13qx:36393] [ 8] plumed(+0x146dd)[0x563202ef16dd]
[runnervmi13qx:36393] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbef842a1ca]
[runnervmi13qx:36393] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbef842a28b]
[runnervmi13qx:36393] [11] plumed(+0x15365)[0x563202ef2365]
[runnervmi13qx:36393] *** End of error message ***
</pre>
{% endraw %}
