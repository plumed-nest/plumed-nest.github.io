**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @43 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:12193] *** Process received signal ***
[pkrvmbietmlfzoi:12193] Signal: Aborted (6)
[pkrvmbietmlfzoi:12193] Signal code:  (-6)
[pkrvmbietmlfzoi:12193] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4266445330]
[pkrvmbietmlfzoi:12193] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f426649eb2c]
[pkrvmbietmlfzoi:12193] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f426644527e]
[pkrvmbietmlfzoi:12193] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f42664288ff]
[pkrvmbietmlfzoi:12193] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f42668a5ff5]
[pkrvmbietmlfzoi:12193] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f42668bb0da]
[pkrvmbietmlfzoi:12193] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f42668a5a55]
[pkrvmbietmlfzoi:12193] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f42668a5a6f]
[pkrvmbietmlfzoi:12193] [ 8] plumed_master(+0x146dd)[0x561ba2de66dd]
[pkrvmbietmlfzoi:12193] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f426642a1ca]
[pkrvmbietmlfzoi:12193] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f426642a28b]
[pkrvmbietmlfzoi:12193] [11] plumed_master(+0x15365)[0x561ba2de7365]
[pkrvmbietmlfzoi:12193] *** End of error message ***
</pre>
{% endraw %}
