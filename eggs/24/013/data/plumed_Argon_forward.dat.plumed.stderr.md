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
[pkrvmbietmlfzoi:62245] *** Process received signal ***
[pkrvmbietmlfzoi:62245] Signal: Aborted (6)
[pkrvmbietmlfzoi:62245] Signal code:  (-6)
[pkrvmbietmlfzoi:62245] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5a7ce45330]
[pkrvmbietmlfzoi:62245] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5a7ce9eb2c]
[pkrvmbietmlfzoi:62245] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5a7ce4527e]
[pkrvmbietmlfzoi:62245] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5a7ce288ff]
[pkrvmbietmlfzoi:62245] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5a7d2a5ff5]
[pkrvmbietmlfzoi:62245] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5a7d2bb0da]
[pkrvmbietmlfzoi:62245] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5a7d2a5a55]
[pkrvmbietmlfzoi:62245] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5a7d2a5a6f]
[pkrvmbietmlfzoi:62245] [ 8] plumed(+0x146dd)[0x5654cd4d46dd]
[pkrvmbietmlfzoi:62245] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5a7ce2a1ca]
[pkrvmbietmlfzoi:62245] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5a7ce2a28b]
[pkrvmbietmlfzoi:62245] [11] plumed(+0x15365)[0x5654cd4d5365]
[pkrvmbietmlfzoi:62245] *** End of error message ***
</pre>
{% endraw %}
