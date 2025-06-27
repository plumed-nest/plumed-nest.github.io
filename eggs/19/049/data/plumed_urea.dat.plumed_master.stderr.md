**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s43 : missing SWITCH11 keyword
[pkrvmbietmlfzoi:69187] *** Process received signal ***
[pkrvmbietmlfzoi:69187] Signal: Aborted (6)
[pkrvmbietmlfzoi:69187] Signal code:  (-6)
[pkrvmbietmlfzoi:69187] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3209a45330]
[pkrvmbietmlfzoi:69187] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3209a9eb2c]
[pkrvmbietmlfzoi:69187] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3209a4527e]
[pkrvmbietmlfzoi:69187] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3209a288ff]
[pkrvmbietmlfzoi:69187] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3209ea5ff5]
[pkrvmbietmlfzoi:69187] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3209ebb0da]
[pkrvmbietmlfzoi:69187] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3209ea5a55]
[pkrvmbietmlfzoi:69187] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3209ea5a6f]
[pkrvmbietmlfzoi:69187] [ 8] plumed_master(+0x146dd)[0x55cebd8a06dd]
[pkrvmbietmlfzoi:69187] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3209a2a1ca]
[pkrvmbietmlfzoi:69187] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3209a2a28b]
[pkrvmbietmlfzoi:69187] [11] plumed_master(+0x15365)[0x55cebd8a1365]
[pkrvmbietmlfzoi:69187] *** End of error message ***
</pre>
{% endraw %}
