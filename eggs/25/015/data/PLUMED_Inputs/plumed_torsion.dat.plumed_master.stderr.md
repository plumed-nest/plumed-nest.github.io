**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[runnervmi13qx:33025] *** Process received signal ***
[runnervmi13qx:33025] Signal: Aborted (6)
[runnervmi13qx:33025] Signal code:  (-6)
[runnervmi13qx:33025] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f67445330]
[runnervmi13qx:33025] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f6749eb2c]
[runnervmi13qx:33025] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f6744527e]
[runnervmi13qx:33025] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f674288ff]
[runnervmi13qx:33025] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f678a5ff5]
[runnervmi13qx:33025] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f678bb0da]
[runnervmi13qx:33025] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f678a5a55]
[runnervmi13qx:33025] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f678a5a6f]
[runnervmi13qx:33025] [ 8] plumed_master(+0x146dd)[0x55f1ba8cf6dd]
[runnervmi13qx:33025] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f6742a1ca]
[runnervmi13qx:33025] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f6742a28b]
[runnervmi13qx:33025] [11] plumed_master(+0x15365)[0x55f1ba8d0365]
[runnervmi13qx:33025] *** End of error message ***
</pre>
{% endraw %}
