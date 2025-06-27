**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:66607] *** Process received signal ***
[pkrvmbietmlfzoi:66607] Signal: Aborted (6)
[pkrvmbietmlfzoi:66607] Signal code:  (-6)
[pkrvmbietmlfzoi:66607] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcbd1445330]
[pkrvmbietmlfzoi:66607] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcbd149eb2c]
[pkrvmbietmlfzoi:66607] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcbd144527e]
[pkrvmbietmlfzoi:66607] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcbd14288ff]
[pkrvmbietmlfzoi:66607] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcbd18a5ff5]
[pkrvmbietmlfzoi:66607] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcbd18bb0da]
[pkrvmbietmlfzoi:66607] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcbd18a5a55]
[pkrvmbietmlfzoi:66607] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcbd18a5a6f]
[pkrvmbietmlfzoi:66607] [ 8] plumed_master(+0x146dd)[0x55dacf3dc6dd]
[pkrvmbietmlfzoi:66607] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcbd142a1ca]
[pkrvmbietmlfzoi:66607] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcbd142a28b]
[pkrvmbietmlfzoi:66607] [11] plumed_master(+0x15365)[0x55dacf3dd365]
[pkrvmbietmlfzoi:66607] *** End of error message ***
</pre>
{% endraw %}
