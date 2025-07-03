**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @59 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:09843] *** Process received signal ***
[pkrvmbietmlfzoi:09843] Signal: Aborted (6)
[pkrvmbietmlfzoi:09843] Signal code:  (-6)
[pkrvmbietmlfzoi:09843] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff75bc45330]
[pkrvmbietmlfzoi:09843] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff75bc9eb2c]
[pkrvmbietmlfzoi:09843] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff75bc4527e]
[pkrvmbietmlfzoi:09843] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff75bc288ff]
[pkrvmbietmlfzoi:09843] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff75c0a5ff5]
[pkrvmbietmlfzoi:09843] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff75c0bb0da]
[pkrvmbietmlfzoi:09843] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff75c0a5a55]
[pkrvmbietmlfzoi:09843] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff75c0a5a6f]
[pkrvmbietmlfzoi:09843] [ 8] plumed_master(+0x146dd)[0x560e798826dd]
[pkrvmbietmlfzoi:09843] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff75bc2a1ca]
[pkrvmbietmlfzoi:09843] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff75bc2a28b]
[pkrvmbietmlfzoi:09843] [11] plumed_master(+0x15365)[0x560e79883365]
[pkrvmbietmlfzoi:09843] *** End of error message ***
</pre>
{% endraw %}
