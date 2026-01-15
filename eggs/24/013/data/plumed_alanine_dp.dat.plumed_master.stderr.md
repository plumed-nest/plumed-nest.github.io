**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[runnervmi13qx:34073] *** Process received signal ***
[runnervmi13qx:34073] Signal: Aborted (6)
[runnervmi13qx:34073] Signal code:  (-6)
[runnervmi13qx:34073] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e18c45330]
[runnervmi13qx:34073] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e18c9eb2c]
[runnervmi13qx:34073] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e18c4527e]
[runnervmi13qx:34073] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e18c288ff]
[runnervmi13qx:34073] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e190a5ff5]
[runnervmi13qx:34073] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e190bb0da]
[runnervmi13qx:34073] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e190a5a55]
[runnervmi13qx:34073] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e190a5a6f]
[runnervmi13qx:34073] [ 8] plumed_master(+0x146dd)[0x55e56afea6dd]
[runnervmi13qx:34073] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e18c2a1ca]
[runnervmi13qx:34073] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e18c2a28b]
[runnervmi13qx:34073] [11] plumed_master(+0x15365)[0x55e56afeb365]
[runnervmi13qx:34073] *** End of error message ***
</pre>
{% endraw %}
