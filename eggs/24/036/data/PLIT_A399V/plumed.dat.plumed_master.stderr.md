**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT_A399V/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:62796] *** Process received signal ***
[pkrvmbietmlfzoi:62796] Signal: Aborted (6)
[pkrvmbietmlfzoi:62796] Signal code:  (-6)
[pkrvmbietmlfzoi:62796] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e9a445330]
[pkrvmbietmlfzoi:62796] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e9a49eb2c]
[pkrvmbietmlfzoi:62796] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e9a44527e]
[pkrvmbietmlfzoi:62796] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e9a4288ff]
[pkrvmbietmlfzoi:62796] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e9a8a5ff5]
[pkrvmbietmlfzoi:62796] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e9a8bb0da]
[pkrvmbietmlfzoi:62796] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e9a8a5a55]
[pkrvmbietmlfzoi:62796] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e9a8a5a6f]
[pkrvmbietmlfzoi:62796] [ 8] plumed_master(+0x146dd)[0x55741abbe6dd]
[pkrvmbietmlfzoi:62796] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e9a42a1ca]
[pkrvmbietmlfzoi:62796] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e9a42a28b]
[pkrvmbietmlfzoi:62796] [11] plumed_master(+0x15365)[0x55741abbf365]
[pkrvmbietmlfzoi:62796] *** End of error message ***
</pre>
{% endraw %}
