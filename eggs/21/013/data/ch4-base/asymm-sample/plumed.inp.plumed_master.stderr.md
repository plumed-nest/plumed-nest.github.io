**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @42 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:09741] *** Process received signal ***
[pkrvmbietmlfzoi:09741] Signal: Aborted (6)
[pkrvmbietmlfzoi:09741] Signal code:  (-6)
[pkrvmbietmlfzoi:09741] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8cd8045330]
[pkrvmbietmlfzoi:09741] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8cd809eb2c]
[pkrvmbietmlfzoi:09741] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8cd804527e]
[pkrvmbietmlfzoi:09741] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8cd80288ff]
[pkrvmbietmlfzoi:09741] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8cd84a5ff5]
[pkrvmbietmlfzoi:09741] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8cd84bb0da]
[pkrvmbietmlfzoi:09741] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8cd84a5a55]
[pkrvmbietmlfzoi:09741] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8cd84a5a6f]
[pkrvmbietmlfzoi:09741] [ 8] plumed_master(+0x146dd)[0x562c383416dd]
[pkrvmbietmlfzoi:09741] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8cd802a1ca]
[pkrvmbietmlfzoi:09741] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8cd802a28b]
[pkrvmbietmlfzoi:09741] [11] plumed_master(+0x15365)[0x562c38342365]
[pkrvmbietmlfzoi:09741] *** End of error message ***
</pre>
{% endraw %}
