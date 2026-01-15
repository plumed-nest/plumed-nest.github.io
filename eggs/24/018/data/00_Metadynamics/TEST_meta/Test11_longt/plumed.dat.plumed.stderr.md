**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmi13qx:32156] *** Process received signal ***
[runnervmi13qx:32156] Signal: Aborted (6)
[runnervmi13qx:32156] Signal code:  (-6)
[runnervmi13qx:32156] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe011e45330]
[runnervmi13qx:32156] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe011e9eb2c]
[runnervmi13qx:32156] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe011e4527e]
[runnervmi13qx:32156] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe011e288ff]
[runnervmi13qx:32156] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe0122a5ff5]
[runnervmi13qx:32156] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe0122bb0da]
[runnervmi13qx:32156] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe0122a5a55]
[runnervmi13qx:32156] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe0122a5a6f]
[runnervmi13qx:32156] [ 8] plumed(+0x146dd)[0x5639c9e806dd]
[runnervmi13qx:32156] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe011e2a1ca]
[runnervmi13qx:32156] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe011e2a28b]
[runnervmi13qx:32156] [11] plumed(+0x15365)[0x5639c9e81365]
[runnervmi13qx:32156] *** End of error message ***
</pre>
{% endraw %}
