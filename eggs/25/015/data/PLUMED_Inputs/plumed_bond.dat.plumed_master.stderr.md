**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervmi13qx:32948] *** Process received signal ***
[runnervmi13qx:32948] Signal: Aborted (6)
[runnervmi13qx:32948] Signal code:  (-6)
[runnervmi13qx:32948] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f68c45330]
[runnervmi13qx:32948] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f68c9eb2c]
[runnervmi13qx:32948] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f68c4527e]
[runnervmi13qx:32948] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f68c288ff]
[runnervmi13qx:32948] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f690a5ff5]
[runnervmi13qx:32948] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f690bb0da]
[runnervmi13qx:32948] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f690a5a55]
[runnervmi13qx:32948] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f690a5a6f]
[runnervmi13qx:32948] [ 8] plumed_master(+0x146dd)[0x56211b4ed6dd]
[runnervmi13qx:32948] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f68c2a1ca]
[runnervmi13qx:32948] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f68c2a28b]
[runnervmi13qx:32948] [11] plumed_master(+0x15365)[0x56211b4ee365]
[runnervmi13qx:32948] *** End of error message ***
</pre>
{% endraw %}
