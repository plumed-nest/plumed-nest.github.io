**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ccl-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:12578] *** Process received signal ***
[pkrvmbietmlfzoi:12578] Signal: Aborted (6)
[pkrvmbietmlfzoi:12578] Signal code:  (-6)
[pkrvmbietmlfzoi:12578] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7671045330]
[pkrvmbietmlfzoi:12578] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f767109eb2c]
[pkrvmbietmlfzoi:12578] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f767104527e]
[pkrvmbietmlfzoi:12578] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76710288ff]
[pkrvmbietmlfzoi:12578] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f76714a5ff5]
[pkrvmbietmlfzoi:12578] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f76714bb0da]
[pkrvmbietmlfzoi:12578] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f76714a5a55]
[pkrvmbietmlfzoi:12578] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f76714a5a6f]
[pkrvmbietmlfzoi:12578] [ 8] plumed_master(+0x146dd)[0x55718c1b66dd]
[pkrvmbietmlfzoi:12578] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f767102a1ca]
[pkrvmbietmlfzoi:12578] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f767102a28b]
[pkrvmbietmlfzoi:12578] [11] plumed_master(+0x15365)[0x55718c1b7365]
[pkrvmbietmlfzoi:12578] *** End of error message ***
</pre>
{% endraw %}
