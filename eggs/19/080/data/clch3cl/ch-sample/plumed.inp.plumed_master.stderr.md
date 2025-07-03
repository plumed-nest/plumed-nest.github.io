**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:12642] *** Process received signal ***
[pkrvmbietmlfzoi:12642] Signal: Aborted (6)
[pkrvmbietmlfzoi:12642] Signal code:  (-6)
[pkrvmbietmlfzoi:12642] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad6fc45330]
[pkrvmbietmlfzoi:12642] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad6fc9eb2c]
[pkrvmbietmlfzoi:12642] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad6fc4527e]
[pkrvmbietmlfzoi:12642] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad6fc288ff]
[pkrvmbietmlfzoi:12642] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad700a5ff5]
[pkrvmbietmlfzoi:12642] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad700bb0da]
[pkrvmbietmlfzoi:12642] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad700a5a55]
[pkrvmbietmlfzoi:12642] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad700a5a6f]
[pkrvmbietmlfzoi:12642] [ 8] plumed_master(+0x146dd)[0x55e5199b86dd]
[pkrvmbietmlfzoi:12642] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad6fc2a1ca]
[pkrvmbietmlfzoi:12642] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad6fc2a28b]
[pkrvmbietmlfzoi:12642] [11] plumed_master(+0x15365)[0x55e5199b9365]
[pkrvmbietmlfzoi:12642] *** End of error message ***
</pre>
{% endraw %}
