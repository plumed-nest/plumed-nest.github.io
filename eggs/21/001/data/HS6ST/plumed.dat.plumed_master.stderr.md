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
[pkrvmbietmlfzoi:12496] *** Process received signal ***
[pkrvmbietmlfzoi:12496] Signal: Aborted (6)
[pkrvmbietmlfzoi:12496] Signal code:  (-6)
[pkrvmbietmlfzoi:12496] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9029c45330]
[pkrvmbietmlfzoi:12496] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9029c9eb2c]
[pkrvmbietmlfzoi:12496] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9029c4527e]
[pkrvmbietmlfzoi:12496] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9029c288ff]
[pkrvmbietmlfzoi:12496] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f902a0a5ff5]
[pkrvmbietmlfzoi:12496] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f902a0bb0da]
[pkrvmbietmlfzoi:12496] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f902a0a5a55]
[pkrvmbietmlfzoi:12496] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f902a0a5a6f]
[pkrvmbietmlfzoi:12496] [ 8] plumed_master(+0x146dd)[0x55a85525f6dd]
[pkrvmbietmlfzoi:12496] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9029c2a1ca]
[pkrvmbietmlfzoi:12496] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9029c2a28b]
[pkrvmbietmlfzoi:12496] [11] plumed_master(+0x15365)[0x55a855260365]
[pkrvmbietmlfzoi:12496] *** End of error message ***
</pre>
{% endraw %}
