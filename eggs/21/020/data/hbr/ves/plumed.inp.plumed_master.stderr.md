**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/ves/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @51 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:12388] *** Process received signal ***
[pkrvmbietmlfzoi:12388] Signal: Aborted (6)
[pkrvmbietmlfzoi:12388] Signal code:  (-6)
[pkrvmbietmlfzoi:12388] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa444c45330]
[pkrvmbietmlfzoi:12388] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa444c9eb2c]
[pkrvmbietmlfzoi:12388] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa444c4527e]
[pkrvmbietmlfzoi:12388] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa444c288ff]
[pkrvmbietmlfzoi:12388] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4450a5ff5]
[pkrvmbietmlfzoi:12388] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4450bb0da]
[pkrvmbietmlfzoi:12388] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4450a5a55]
[pkrvmbietmlfzoi:12388] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4450a5a6f]
[pkrvmbietmlfzoi:12388] [ 8] plumed_master(+0x146dd)[0x556989f5d6dd]
[pkrvmbietmlfzoi:12388] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa444c2a1ca]
[pkrvmbietmlfzoi:12388] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa444c2a28b]
[pkrvmbietmlfzoi:12388] [11] plumed_master(+0x15365)[0x556989f5e365]
[pkrvmbietmlfzoi:12388] *** End of error message ***
</pre>
{% endraw %}
