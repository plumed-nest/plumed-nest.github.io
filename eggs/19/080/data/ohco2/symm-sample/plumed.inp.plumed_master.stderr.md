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
[pkrvmbietmlfzoi:12365] *** Process received signal ***
[pkrvmbietmlfzoi:12365] Signal: Aborted (6)
[pkrvmbietmlfzoi:12365] Signal code:  (-6)
[pkrvmbietmlfzoi:12365] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0b2d045330]
[pkrvmbietmlfzoi:12365] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0b2d09eb2c]
[pkrvmbietmlfzoi:12365] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0b2d04527e]
[pkrvmbietmlfzoi:12365] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0b2d0288ff]
[pkrvmbietmlfzoi:12365] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0b2d4a5ff5]
[pkrvmbietmlfzoi:12365] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0b2d4bb0da]
[pkrvmbietmlfzoi:12365] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0b2d4a5a55]
[pkrvmbietmlfzoi:12365] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0b2d4a5a6f]
[pkrvmbietmlfzoi:12365] [ 8] plumed_master(+0x146dd)[0x5559a1bda6dd]
[pkrvmbietmlfzoi:12365] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0b2d02a1ca]
[pkrvmbietmlfzoi:12365] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0b2d02a28b]
[pkrvmbietmlfzoi:12365] [11] plumed_master(+0x15365)[0x5559a1bdb365]
[pkrvmbietmlfzoi:12365] *** End of error message ***
</pre>
{% endraw %}
