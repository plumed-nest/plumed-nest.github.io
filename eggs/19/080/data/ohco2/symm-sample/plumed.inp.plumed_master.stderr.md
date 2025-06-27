**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:66670] *** Process received signal ***
[pkrvmbietmlfzoi:66670] Signal: Aborted (6)
[pkrvmbietmlfzoi:66670] Signal code:  (-6)
[pkrvmbietmlfzoi:66670] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc04e45330]
[pkrvmbietmlfzoi:66670] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc04e9eb2c]
[pkrvmbietmlfzoi:66670] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc04e4527e]
[pkrvmbietmlfzoi:66670] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc04e288ff]
[pkrvmbietmlfzoi:66670] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc052a5ff5]
[pkrvmbietmlfzoi:66670] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc052bb0da]
[pkrvmbietmlfzoi:66670] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc052a5a55]
[pkrvmbietmlfzoi:66670] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc052a5a6f]
[pkrvmbietmlfzoi:66670] [ 8] plumed_master(+0x146dd)[0x56003db726dd]
[pkrvmbietmlfzoi:66670] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc04e2a1ca]
[pkrvmbietmlfzoi:66670] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc04e2a28b]
[pkrvmbietmlfzoi:66670] [11] plumed_master(+0x15365)[0x56003db73365]
[pkrvmbietmlfzoi:66670] *** End of error message ***
</pre>
{% endraw %}
