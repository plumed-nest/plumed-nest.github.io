**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/opes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @48 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:12426] *** Process received signal ***
[pkrvmbietmlfzoi:12426] Signal: Aborted (6)
[pkrvmbietmlfzoi:12426] Signal code:  (-6)
[pkrvmbietmlfzoi:12426] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2d14045330]
[pkrvmbietmlfzoi:12426] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2d1409eb2c]
[pkrvmbietmlfzoi:12426] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2d1404527e]
[pkrvmbietmlfzoi:12426] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2d140288ff]
[pkrvmbietmlfzoi:12426] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2d144a5ff5]
[pkrvmbietmlfzoi:12426] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2d144bb0da]
[pkrvmbietmlfzoi:12426] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2d144a5a55]
[pkrvmbietmlfzoi:12426] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2d144a5a6f]
[pkrvmbietmlfzoi:12426] [ 8] plumed_master(+0x146dd)[0x55c4368436dd]
[pkrvmbietmlfzoi:12426] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2d1402a1ca]
[pkrvmbietmlfzoi:12426] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2d1402a28b]
[pkrvmbietmlfzoi:12426] [11] plumed_master(+0x15365)[0x55c436844365]
[pkrvmbietmlfzoi:12426] *** End of error message ***
</pre>
{% endraw %}
