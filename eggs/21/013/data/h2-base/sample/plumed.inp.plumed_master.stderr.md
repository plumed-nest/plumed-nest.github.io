**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-base/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @28 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:10481] *** Process received signal ***
[pkrvmbietmlfzoi:10481] Signal: Aborted (6)
[pkrvmbietmlfzoi:10481] Signal code:  (-6)
[pkrvmbietmlfzoi:10481] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0b7ee45330]
[pkrvmbietmlfzoi:10481] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0b7ee9eb2c]
[pkrvmbietmlfzoi:10481] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0b7ee4527e]
[pkrvmbietmlfzoi:10481] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0b7ee288ff]
[pkrvmbietmlfzoi:10481] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0b7f2a5ff5]
[pkrvmbietmlfzoi:10481] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0b7f2bb0da]
[pkrvmbietmlfzoi:10481] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0b7f2a5a55]
[pkrvmbietmlfzoi:10481] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0b7f2a5a6f]
[pkrvmbietmlfzoi:10481] [ 8] plumed_master(+0x146dd)[0x5613a3d176dd]
[pkrvmbietmlfzoi:10481] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0b7ee2a1ca]
[pkrvmbietmlfzoi:10481] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0b7ee2a28b]
[pkrvmbietmlfzoi:10481] [11] plumed_master(+0x15365)[0x5613a3d18365]
[pkrvmbietmlfzoi:10481] *** End of error message ***
</pre>
{% endraw %}
