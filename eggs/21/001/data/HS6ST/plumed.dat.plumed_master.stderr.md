**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS6ST/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:67655] *** Process received signal ***
[pkrvmbietmlfzoi:67655] Signal: Aborted (6)
[pkrvmbietmlfzoi:67655] Signal code:  (-6)
[pkrvmbietmlfzoi:67655] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1c90645330]
[pkrvmbietmlfzoi:67655] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1c9069eb2c]
[pkrvmbietmlfzoi:67655] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1c9064527e]
[pkrvmbietmlfzoi:67655] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1c906288ff]
[pkrvmbietmlfzoi:67655] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1c90aa5ff5]
[pkrvmbietmlfzoi:67655] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1c90abb0da]
[pkrvmbietmlfzoi:67655] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1c90aa5a55]
[pkrvmbietmlfzoi:67655] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1c90aa5a6f]
[pkrvmbietmlfzoi:67655] [ 8] plumed_master(+0x146dd)[0x564e56c606dd]
[pkrvmbietmlfzoi:67655] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1c9062a1ca]
[pkrvmbietmlfzoi:67655] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1c9062a28b]
[pkrvmbietmlfzoi:67655] [11] plumed_master(+0x15365)[0x564e56c61365]
[pkrvmbietmlfzoi:67655] *** End of error message ***
</pre>
{% endraw %}
