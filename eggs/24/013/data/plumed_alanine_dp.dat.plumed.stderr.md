**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[runnervmi13qx:34057] *** Process received signal ***
[runnervmi13qx:34057] Signal: Aborted (6)
[runnervmi13qx:34057] Signal code:  (-6)
[runnervmi13qx:34057] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd53dc45330]
[runnervmi13qx:34057] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd53dc9eb2c]
[runnervmi13qx:34057] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd53dc4527e]
[runnervmi13qx:34057] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd53dc288ff]
[runnervmi13qx:34057] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd53e0a5ff5]
[runnervmi13qx:34057] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd53e0bb0da]
[runnervmi13qx:34057] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd53e0a5a55]
[runnervmi13qx:34057] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd53e0a5a6f]
[runnervmi13qx:34057] [ 8] plumed(+0x146dd)[0x55e161f596dd]
[runnervmi13qx:34057] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd53dc2a1ca]
[runnervmi13qx:34057] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd53dc2a28b]
[runnervmi13qx:34057] [11] plumed(+0x15365)[0x55e161f5a365]
[runnervmi13qx:34057] *** End of error message ***
</pre>
{% endraw %}
