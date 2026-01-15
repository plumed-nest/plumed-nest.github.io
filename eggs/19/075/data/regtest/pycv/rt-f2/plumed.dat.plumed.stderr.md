**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervmi13qx:38918] *** Process received signal ***
[runnervmi13qx:38918] Signal: Aborted (6)
[runnervmi13qx:38918] Signal code:  (-6)
[runnervmi13qx:38918] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdfe8a45330]
[runnervmi13qx:38918] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdfe8a9eb2c]
[runnervmi13qx:38918] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdfe8a4527e]
[runnervmi13qx:38918] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdfe8a288ff]
[runnervmi13qx:38918] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdfe8ea5ff5]
[runnervmi13qx:38918] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdfe8ebb0da]
[runnervmi13qx:38918] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdfe8ea5a55]
[runnervmi13qx:38918] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdfe8ea5a6f]
[runnervmi13qx:38918] [ 8] plumed(+0x146dd)[0x55e51888a6dd]
[runnervmi13qx:38918] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdfe8a2a1ca]
[runnervmi13qx:38918] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdfe8a2a28b]
[runnervmi13qx:38918] [11] plumed(+0x15365)[0x55e51888b365]
[runnervmi13qx:38918] *** End of error message ***
</pre>
{% endraw %}
