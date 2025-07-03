**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @89 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:07747] *** Process received signal ***
[pkrvmbietmlfzoi:07747] Signal: Aborted (6)
[pkrvmbietmlfzoi:07747] Signal code:  (-6)
[pkrvmbietmlfzoi:07747] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b96e45330]
[pkrvmbietmlfzoi:07747] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b96e9eb2c]
[pkrvmbietmlfzoi:07747] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b96e4527e]
[pkrvmbietmlfzoi:07747] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b96e288ff]
[pkrvmbietmlfzoi:07747] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b972a5ff5]
[pkrvmbietmlfzoi:07747] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b972bb0da]
[pkrvmbietmlfzoi:07747] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b972a5a55]
[pkrvmbietmlfzoi:07747] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b972a5a6f]
[pkrvmbietmlfzoi:07747] [ 8] plumed_master(+0x146dd)[0x55e6be42a6dd]
[pkrvmbietmlfzoi:07747] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b96e2a1ca]
[pkrvmbietmlfzoi:07747] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b96e2a28b]
[pkrvmbietmlfzoi:07747] [11] plumed_master(+0x15365)[0x55e6be42b365]
[pkrvmbietmlfzoi:07747] *** End of error message ***
</pre>
{% endraw %}
