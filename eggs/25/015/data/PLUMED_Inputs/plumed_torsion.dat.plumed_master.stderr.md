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
[pkrvmbietmlfzoi:05626] *** Process received signal ***
[pkrvmbietmlfzoi:05626] Signal: Aborted (6)
[pkrvmbietmlfzoi:05626] Signal code:  (-6)
[pkrvmbietmlfzoi:05626] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd673645330]
[pkrvmbietmlfzoi:05626] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd67369eb2c]
[pkrvmbietmlfzoi:05626] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd67364527e]
[pkrvmbietmlfzoi:05626] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6736288ff]
[pkrvmbietmlfzoi:05626] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd673aa5ff5]
[pkrvmbietmlfzoi:05626] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd673abb0da]
[pkrvmbietmlfzoi:05626] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd673aa5a55]
[pkrvmbietmlfzoi:05626] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd673aa5a6f]
[pkrvmbietmlfzoi:05626] [ 8] plumed_master(+0x146dd)[0x564efd1256dd]
[pkrvmbietmlfzoi:05626] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd67362a1ca]
[pkrvmbietmlfzoi:05626] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd67362a28b]
[pkrvmbietmlfzoi:05626] [11] plumed_master(+0x15365)[0x564efd126365]
[pkrvmbietmlfzoi:05626] *** End of error message ***
</pre>
{% endraw %}
