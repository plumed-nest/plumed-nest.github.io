**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmbietmlfzoi:05902] *** Process received signal ***
[pkrvmbietmlfzoi:05902] Signal: Aborted (6)
[pkrvmbietmlfzoi:05902] Signal code:  (-6)
[pkrvmbietmlfzoi:05902] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5f9be45330]
[pkrvmbietmlfzoi:05902] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5f9be9eb2c]
[pkrvmbietmlfzoi:05902] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5f9be4527e]
[pkrvmbietmlfzoi:05902] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5f9be288ff]
[pkrvmbietmlfzoi:05902] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5f9c2a5ff5]
[pkrvmbietmlfzoi:05902] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5f9c2bb0da]
[pkrvmbietmlfzoi:05902] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5f9c2a5a55]
[pkrvmbietmlfzoi:05902] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5f9c2a5a6f]
[pkrvmbietmlfzoi:05902] [ 8] plumed_master(+0x146dd)[0x556ed91b66dd]
[pkrvmbietmlfzoi:05902] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5f9be2a1ca]
[pkrvmbietmlfzoi:05902] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5f9be2a28b]
[pkrvmbietmlfzoi:05902] [11] plumed_master(+0x15365)[0x556ed91b7365]
[pkrvmbietmlfzoi:05902] *** End of error message ***
</pre>
{% endraw %}
