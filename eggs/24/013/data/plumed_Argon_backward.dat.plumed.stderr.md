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
[pkrvmbietmlfzoi:06348] *** Process received signal ***
[pkrvmbietmlfzoi:06348] Signal: Aborted (6)
[pkrvmbietmlfzoi:06348] Signal code:  (-6)
[pkrvmbietmlfzoi:06348] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f765ac45330]
[pkrvmbietmlfzoi:06348] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f765ac9eb2c]
[pkrvmbietmlfzoi:06348] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f765ac4527e]
[pkrvmbietmlfzoi:06348] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f765ac288ff]
[pkrvmbietmlfzoi:06348] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f765b0a5ff5]
[pkrvmbietmlfzoi:06348] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f765b0bb0da]
[pkrvmbietmlfzoi:06348] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f765b0a5a55]
[pkrvmbietmlfzoi:06348] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f765b0a5a6f]
[pkrvmbietmlfzoi:06348] [ 8] plumed(+0x146dd)[0x5631c5a766dd]
[pkrvmbietmlfzoi:06348] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f765ac2a1ca]
[pkrvmbietmlfzoi:06348] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f765ac2a28b]
[pkrvmbietmlfzoi:06348] [11] plumed(+0x15365)[0x5631c5a77365]
[pkrvmbietmlfzoi:06348] *** End of error message ***
</pre>
{% endraw %}
