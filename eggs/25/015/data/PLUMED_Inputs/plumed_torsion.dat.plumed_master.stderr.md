**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[pkrvmbietmlfzoi:61887] *** Process received signal ***
[pkrvmbietmlfzoi:61887] Signal: Aborted (6)
[pkrvmbietmlfzoi:61887] Signal code:  (-6)
[pkrvmbietmlfzoi:61887] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda83c45330]
[pkrvmbietmlfzoi:61887] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda83c9eb2c]
[pkrvmbietmlfzoi:61887] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda83c4527e]
[pkrvmbietmlfzoi:61887] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda83c288ff]
[pkrvmbietmlfzoi:61887] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda840a5ff5]
[pkrvmbietmlfzoi:61887] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda840bb0da]
[pkrvmbietmlfzoi:61887] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda840a5a55]
[pkrvmbietmlfzoi:61887] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda840a5a6f]
[pkrvmbietmlfzoi:61887] [ 8] plumed_master(+0x146dd)[0x55e3c18236dd]
[pkrvmbietmlfzoi:61887] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda83c2a1ca]
[pkrvmbietmlfzoi:61887] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda83c2a28b]
[pkrvmbietmlfzoi:61887] [11] plumed_master(+0x15365)[0x55e3c1824365]
[pkrvmbietmlfzoi:61887] *** End of error message ***
</pre>
{% endraw %}
