**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/opes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @48 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:66048] *** Process received signal ***
[pkrvmbietmlfzoi:66048] Signal: Aborted (6)
[pkrvmbietmlfzoi:66048] Signal code:  (-6)
[pkrvmbietmlfzoi:66048] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8236845330]
[pkrvmbietmlfzoi:66048] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f823689eb2c]
[pkrvmbietmlfzoi:66048] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f823684527e]
[pkrvmbietmlfzoi:66048] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f82368288ff]
[pkrvmbietmlfzoi:66048] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8236ca5ff5]
[pkrvmbietmlfzoi:66048] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8236cbb0da]
[pkrvmbietmlfzoi:66048] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8236ca5a55]
[pkrvmbietmlfzoi:66048] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8236ca5a6f]
[pkrvmbietmlfzoi:66048] [ 8] plumed_master(+0x146dd)[0x5565656f56dd]
[pkrvmbietmlfzoi:66048] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f823682a1ca]
[pkrvmbietmlfzoi:66048] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f823682a28b]
[pkrvmbietmlfzoi:66048] [11] plumed_master(+0x15365)[0x5565656f6365]
[pkrvmbietmlfzoi:66048] *** End of error message ***
</pre>
{% endraw %}
