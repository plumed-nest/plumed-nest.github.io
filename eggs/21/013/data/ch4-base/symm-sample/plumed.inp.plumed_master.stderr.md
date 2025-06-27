**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:66427] *** Process received signal ***
[pkrvmbietmlfzoi:66427] Signal: Aborted (6)
[pkrvmbietmlfzoi:66427] Signal code:  (-6)
[pkrvmbietmlfzoi:66427] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ca2a45330]
[pkrvmbietmlfzoi:66427] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ca2a9eb2c]
[pkrvmbietmlfzoi:66427] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ca2a4527e]
[pkrvmbietmlfzoi:66427] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ca2a288ff]
[pkrvmbietmlfzoi:66427] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ca2ea5ff5]
[pkrvmbietmlfzoi:66427] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ca2ebb0da]
[pkrvmbietmlfzoi:66427] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ca2ea5a55]
[pkrvmbietmlfzoi:66427] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ca2ea5a6f]
[pkrvmbietmlfzoi:66427] [ 8] plumed_master(+0x146dd)[0x5648886086dd]
[pkrvmbietmlfzoi:66427] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ca2a2a1ca]
[pkrvmbietmlfzoi:66427] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ca2a2a28b]
[pkrvmbietmlfzoi:66427] [11] plumed_master(+0x15365)[0x564888609365]
[pkrvmbietmlfzoi:66427] *** End of error message ***
</pre>
{% endraw %}
