**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmi13qx:34631] *** Process received signal ***
[runnervmi13qx:34631] Signal: Aborted (6)
[runnervmi13qx:34631] Signal code:  (-6)
[runnervmi13qx:34631] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1702a45330]
[runnervmi13qx:34631] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1702a9eb2c]
[runnervmi13qx:34631] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1702a4527e]
[runnervmi13qx:34631] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1702a288ff]
[runnervmi13qx:34631] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1702ea5ff5]
[runnervmi13qx:34631] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1702ebb0da]
[runnervmi13qx:34631] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1702ea5a55]
[runnervmi13qx:34631] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1702ea5a6f]
[runnervmi13qx:34631] [ 8] plumed(+0x146dd)[0x560a1195b6dd]
[runnervmi13qx:34631] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1702a2a1ca]
[runnervmi13qx:34631] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1702a2a28b]
[runnervmi13qx:34631] [11] plumed(+0x15365)[0x560a1195c365]
[runnervmi13qx:34631] *** End of error message ***
</pre>
{% endraw %}
