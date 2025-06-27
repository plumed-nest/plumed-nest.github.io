**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:67141] *** Process received signal ***
[pkrvmbietmlfzoi:67141] Signal: Aborted (6)
[pkrvmbietmlfzoi:67141] Signal code:  (-6)
[pkrvmbietmlfzoi:67141] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f814de45330]
[pkrvmbietmlfzoi:67141] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f814de9eb2c]
[pkrvmbietmlfzoi:67141] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f814de4527e]
[pkrvmbietmlfzoi:67141] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f814de288ff]
[pkrvmbietmlfzoi:67141] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f814e2a5ff5]
[pkrvmbietmlfzoi:67141] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f814e2bb0da]
[pkrvmbietmlfzoi:67141] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f814e2a5a55]
[pkrvmbietmlfzoi:67141] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f814e2a5a6f]
[pkrvmbietmlfzoi:67141] [ 8] plumed_master(+0x146dd)[0x557be9ad06dd]
[pkrvmbietmlfzoi:67141] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f814de2a1ca]
[pkrvmbietmlfzoi:67141] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f814de2a28b]
[pkrvmbietmlfzoi:67141] [11] plumed_master(+0x15365)[0x557be9ad1365]
[pkrvmbietmlfzoi:67141] *** End of error message ***
</pre>
{% endraw %}
