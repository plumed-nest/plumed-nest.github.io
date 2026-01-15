**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmi13qx:39126] *** Process received signal ***
[runnervmi13qx:39126] Signal: Aborted (6)
[runnervmi13qx:39126] Signal code:  (-6)
[runnervmi13qx:39126] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f90fc245330]
[runnervmi13qx:39126] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f90fc29eb2c]
[runnervmi13qx:39126] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f90fc24527e]
[runnervmi13qx:39126] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f90fc2288ff]
[runnervmi13qx:39126] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f90fc6a5ff5]
[runnervmi13qx:39126] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f90fc6bb0da]
[runnervmi13qx:39126] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f90fc6a5a55]
[runnervmi13qx:39126] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f90fc6a5a6f]
[runnervmi13qx:39126] [ 8] plumed(+0x146dd)[0x562da47d06dd]
[runnervmi13qx:39126] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f90fc22a1ca]
[runnervmi13qx:39126] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f90fc22a28b]
[runnervmi13qx:39126] [11] plumed(+0x15365)[0x562da47d1365]
[runnervmi13qx:39126] *** End of error message ***
</pre>
{% endraw %}
