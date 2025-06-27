**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmbietmlfzoi:62194] *** Process received signal ***
[pkrvmbietmlfzoi:62194] Signal: Aborted (6)
[pkrvmbietmlfzoi:62194] Signal code:  (-6)
[pkrvmbietmlfzoi:62194] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f6b645330]
[pkrvmbietmlfzoi:62194] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f6b69eb2c]
[pkrvmbietmlfzoi:62194] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f6b64527e]
[pkrvmbietmlfzoi:62194] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f6b6288ff]
[pkrvmbietmlfzoi:62194] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f6baa5ff5]
[pkrvmbietmlfzoi:62194] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f6babb0da]
[pkrvmbietmlfzoi:62194] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f6baa5a55]
[pkrvmbietmlfzoi:62194] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f6baa5a6f]
[pkrvmbietmlfzoi:62194] [ 8] plumed(+0x146dd)[0x5625b06e96dd]
[pkrvmbietmlfzoi:62194] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f6b62a1ca]
[pkrvmbietmlfzoi:62194] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f6b62a28b]
[pkrvmbietmlfzoi:62194] [11] plumed(+0x15365)[0x5625b06ea365]
[pkrvmbietmlfzoi:62194] *** End of error message ***
</pre>
{% endraw %}
