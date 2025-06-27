**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:62578] *** Process received signal ***
[pkrvmbietmlfzoi:62578] Signal: Aborted (6)
[pkrvmbietmlfzoi:62578] Signal code:  (-6)
[pkrvmbietmlfzoi:62578] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1c75e45330]
[pkrvmbietmlfzoi:62578] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1c75e9eb2c]
[pkrvmbietmlfzoi:62578] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1c75e4527e]
[pkrvmbietmlfzoi:62578] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1c75e288ff]
[pkrvmbietmlfzoi:62578] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1c762a5ff5]
[pkrvmbietmlfzoi:62578] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1c762bb0da]
[pkrvmbietmlfzoi:62578] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1c762a5a55]
[pkrvmbietmlfzoi:62578] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1c762a5a6f]
[pkrvmbietmlfzoi:62578] [ 8] plumed_master(+0x146dd)[0x55d5839c66dd]
[pkrvmbietmlfzoi:62578] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1c75e2a1ca]
[pkrvmbietmlfzoi:62578] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1c75e2a28b]
[pkrvmbietmlfzoi:62578] [11] plumed_master(+0x15365)[0x55d5839c7365]
[pkrvmbietmlfzoi:62578] *** End of error message ***
</pre>
{% endraw %}
