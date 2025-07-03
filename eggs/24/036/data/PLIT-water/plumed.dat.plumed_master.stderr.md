**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:06124] *** Process received signal ***
[pkrvmbietmlfzoi:06124] Signal: Aborted (6)
[pkrvmbietmlfzoi:06124] Signal code:  (-6)
[pkrvmbietmlfzoi:06124] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f10f9a45330]
[pkrvmbietmlfzoi:06124] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f10f9a9eb2c]
[pkrvmbietmlfzoi:06124] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f10f9a4527e]
[pkrvmbietmlfzoi:06124] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10f9a288ff]
[pkrvmbietmlfzoi:06124] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f10f9ea5ff5]
[pkrvmbietmlfzoi:06124] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f10f9ebb0da]
[pkrvmbietmlfzoi:06124] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f10f9ea5a55]
[pkrvmbietmlfzoi:06124] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f10f9ea5a6f]
[pkrvmbietmlfzoi:06124] [ 8] plumed_master(+0x146dd)[0x564bf912d6dd]
[pkrvmbietmlfzoi:06124] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f10f9a2a1ca]
[pkrvmbietmlfzoi:06124] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f10f9a2a28b]
[pkrvmbietmlfzoi:06124] [11] plumed_master(+0x15365)[0x564bf912e365]
[pkrvmbietmlfzoi:06124] *** End of error message ***
</pre>
{% endraw %}
