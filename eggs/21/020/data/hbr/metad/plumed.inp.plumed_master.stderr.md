**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @51 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:12349] *** Process received signal ***
[pkrvmbietmlfzoi:12349] Signal: Aborted (6)
[pkrvmbietmlfzoi:12349] Signal code:  (-6)
[pkrvmbietmlfzoi:12349] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feb69245330]
[pkrvmbietmlfzoi:12349] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feb6929eb2c]
[pkrvmbietmlfzoi:12349] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feb6924527e]
[pkrvmbietmlfzoi:12349] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feb692288ff]
[pkrvmbietmlfzoi:12349] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feb696a5ff5]
[pkrvmbietmlfzoi:12349] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feb696bb0da]
[pkrvmbietmlfzoi:12349] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feb696a5a55]
[pkrvmbietmlfzoi:12349] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feb696a5a6f]
[pkrvmbietmlfzoi:12349] [ 8] plumed_master(+0x146dd)[0x55e3d09056dd]
[pkrvmbietmlfzoi:12349] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feb6922a1ca]
[pkrvmbietmlfzoi:12349] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feb6922a28b]
[pkrvmbietmlfzoi:12349] [11] plumed_master(+0x15365)[0x55e3d0906365]
[pkrvmbietmlfzoi:12349] *** End of error message ***
</pre>
{% endraw %}
