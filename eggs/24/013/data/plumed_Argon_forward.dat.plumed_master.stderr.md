**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmbietmlfzoi:06419] *** Process received signal ***
[pkrvmbietmlfzoi:06419] Signal: Aborted (6)
[pkrvmbietmlfzoi:06419] Signal code:  (-6)
[pkrvmbietmlfzoi:06419] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f97cb845330]
[pkrvmbietmlfzoi:06419] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f97cb89eb2c]
[pkrvmbietmlfzoi:06419] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f97cb84527e]
[pkrvmbietmlfzoi:06419] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97cb8288ff]
[pkrvmbietmlfzoi:06419] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f97cbca5ff5]
[pkrvmbietmlfzoi:06419] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f97cbcbb0da]
[pkrvmbietmlfzoi:06419] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f97cbca5a55]
[pkrvmbietmlfzoi:06419] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f97cbca5a6f]
[pkrvmbietmlfzoi:06419] [ 8] plumed_master(+0x146dd)[0x55e5c0b6f6dd]
[pkrvmbietmlfzoi:06419] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f97cb82a1ca]
[pkrvmbietmlfzoi:06419] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f97cb82a28b]
[pkrvmbietmlfzoi:06419] [11] plumed_master(+0x15365)[0x55e5c0b70365]
[pkrvmbietmlfzoi:06419] *** End of error message ***
</pre>
{% endraw %}
