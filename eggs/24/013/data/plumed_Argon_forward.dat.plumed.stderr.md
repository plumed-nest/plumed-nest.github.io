**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmbietmlfzoi:06403] *** Process received signal ***
[pkrvmbietmlfzoi:06403] Signal: Aborted (6)
[pkrvmbietmlfzoi:06403] Signal code:  (-6)
[pkrvmbietmlfzoi:06403] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f79ece45330]
[pkrvmbietmlfzoi:06403] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f79ece9eb2c]
[pkrvmbietmlfzoi:06403] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f79ece4527e]
[pkrvmbietmlfzoi:06403] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79ece288ff]
[pkrvmbietmlfzoi:06403] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f79ed2a5ff5]
[pkrvmbietmlfzoi:06403] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f79ed2bb0da]
[pkrvmbietmlfzoi:06403] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f79ed2a5a55]
[pkrvmbietmlfzoi:06403] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f79ed2a5a6f]
[pkrvmbietmlfzoi:06403] [ 8] plumed(+0x146dd)[0x5651771cb6dd]
[pkrvmbietmlfzoi:06403] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f79ece2a1ca]
[pkrvmbietmlfzoi:06403] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f79ece2a28b]
[pkrvmbietmlfzoi:06403] [11] plumed(+0x15365)[0x5651771cc365]
[pkrvmbietmlfzoi:06403] *** End of error message ***
</pre>
{% endraw %}
