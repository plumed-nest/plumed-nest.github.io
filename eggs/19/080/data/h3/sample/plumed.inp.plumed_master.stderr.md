**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:12821] *** Process received signal ***
[pkrvmbietmlfzoi:12821] Signal: Aborted (6)
[pkrvmbietmlfzoi:12821] Signal code:  (-6)
[pkrvmbietmlfzoi:12821] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7554845330]
[pkrvmbietmlfzoi:12821] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f755489eb2c]
[pkrvmbietmlfzoi:12821] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f755484527e]
[pkrvmbietmlfzoi:12821] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f75548288ff]
[pkrvmbietmlfzoi:12821] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7554ca5ff5]
[pkrvmbietmlfzoi:12821] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7554cbb0da]
[pkrvmbietmlfzoi:12821] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7554ca5a55]
[pkrvmbietmlfzoi:12821] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7554ca5a6f]
[pkrvmbietmlfzoi:12821] [ 8] plumed_master(+0x146dd)[0x5608151d36dd]
[pkrvmbietmlfzoi:12821] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f755482a1ca]
[pkrvmbietmlfzoi:12821] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f755482a28b]
[pkrvmbietmlfzoi:12821] [11] plumed_master(+0x15365)[0x5608151d4365]
[pkrvmbietmlfzoi:12821] *** End of error message ***
</pre>
{% endraw %}
