**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmbietmlfzoi:06363] *** Process received signal ***
[pkrvmbietmlfzoi:06363] Signal: Aborted (6)
[pkrvmbietmlfzoi:06363] Signal code:  (-6)
[pkrvmbietmlfzoi:06363] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef61245330]
[pkrvmbietmlfzoi:06363] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef6129eb2c]
[pkrvmbietmlfzoi:06363] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef6124527e]
[pkrvmbietmlfzoi:06363] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef612288ff]
[pkrvmbietmlfzoi:06363] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef616a5ff5]
[pkrvmbietmlfzoi:06363] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef616bb0da]
[pkrvmbietmlfzoi:06363] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef616a5a55]
[pkrvmbietmlfzoi:06363] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef616a5a6f]
[pkrvmbietmlfzoi:06363] [ 8] plumed_master(+0x146dd)[0x5588054646dd]
[pkrvmbietmlfzoi:06363] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef6122a1ca]
[pkrvmbietmlfzoi:06363] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef6122a28b]
[pkrvmbietmlfzoi:06363] [11] plumed_master(+0x15365)[0x558805465365]
[pkrvmbietmlfzoi:06363] *** End of error message ***
</pre>
{% endraw %}
