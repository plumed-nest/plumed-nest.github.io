**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @48 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:62655] *** Process received signal ***
[pkrvmbietmlfzoi:62655] Signal: Aborted (6)
[pkrvmbietmlfzoi:62655] Signal code:  (-6)
[pkrvmbietmlfzoi:62655] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff0b9e45330]
[pkrvmbietmlfzoi:62655] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff0b9e9eb2c]
[pkrvmbietmlfzoi:62655] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff0b9e4527e]
[pkrvmbietmlfzoi:62655] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff0b9e288ff]
[pkrvmbietmlfzoi:62655] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff0ba2a5ff5]
[pkrvmbietmlfzoi:62655] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff0ba2bb0da]
[pkrvmbietmlfzoi:62655] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff0ba2a5a55]
[pkrvmbietmlfzoi:62655] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff0ba2a5a6f]
[pkrvmbietmlfzoi:62655] [ 8] plumed_master(+0x146dd)[0x56531e5b56dd]
[pkrvmbietmlfzoi:62655] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff0b9e2a1ca]
[pkrvmbietmlfzoi:62655] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff0b9e2a28b]
[pkrvmbietmlfzoi:62655] [11] plumed_master(+0x15365)[0x56531e5b6365]
[pkrvmbietmlfzoi:62655] *** End of error message ***
</pre>
{% endraw %}
