**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:67051] *** Process received signal ***
[pkrvmbietmlfzoi:67051] Signal: Aborted (6)
[pkrvmbietmlfzoi:67051] Signal code:  (-6)
[pkrvmbietmlfzoi:67051] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6624245330]
[pkrvmbietmlfzoi:67051] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f662429eb2c]
[pkrvmbietmlfzoi:67051] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f662424527e]
[pkrvmbietmlfzoi:67051] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f66242288ff]
[pkrvmbietmlfzoi:67051] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f66246a5ff5]
[pkrvmbietmlfzoi:67051] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f66246bb0da]
[pkrvmbietmlfzoi:67051] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f66246a5a55]
[pkrvmbietmlfzoi:67051] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f66246a5a6f]
[pkrvmbietmlfzoi:67051] [ 8] plumed_master(+0x146dd)[0x5590c6b496dd]
[pkrvmbietmlfzoi:67051] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f662422a1ca]
[pkrvmbietmlfzoi:67051] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f662422a28b]
[pkrvmbietmlfzoi:67051] [11] plumed_master(+0x15365)[0x5590c6b4a365]
[pkrvmbietmlfzoi:67051] *** End of error message ***
</pre>
{% endraw %}
