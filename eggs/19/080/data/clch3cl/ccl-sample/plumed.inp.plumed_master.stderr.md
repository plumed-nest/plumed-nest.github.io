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
[pkrvmbietmlfzoi:66899] *** Process received signal ***
[pkrvmbietmlfzoi:66899] Signal: Aborted (6)
[pkrvmbietmlfzoi:66899] Signal code:  (-6)
[pkrvmbietmlfzoi:66899] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f27ce045330]
[pkrvmbietmlfzoi:66899] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f27ce09eb2c]
[pkrvmbietmlfzoi:66899] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f27ce04527e]
[pkrvmbietmlfzoi:66899] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f27ce0288ff]
[pkrvmbietmlfzoi:66899] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f27ce4a5ff5]
[pkrvmbietmlfzoi:66899] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f27ce4bb0da]
[pkrvmbietmlfzoi:66899] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f27ce4a5a55]
[pkrvmbietmlfzoi:66899] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f27ce4a5a6f]
[pkrvmbietmlfzoi:66899] [ 8] plumed_master(+0x146dd)[0x55edd64346dd]
[pkrvmbietmlfzoi:66899] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f27ce02a1ca]
[pkrvmbietmlfzoi:66899] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f27ce02a28b]
[pkrvmbietmlfzoi:66899] [11] plumed_master(+0x15365)[0x55edd6435365]
[pkrvmbietmlfzoi:66899] *** End of error message ***
</pre>
{% endraw %}
