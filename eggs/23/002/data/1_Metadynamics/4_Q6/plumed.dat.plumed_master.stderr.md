**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s29 : cannot understand the following words from the input line : LOWMEM
[pkrvmbietmlfzoi:63197] *** Process received signal ***
[pkrvmbietmlfzoi:63197] Signal: Aborted (6)
[pkrvmbietmlfzoi:63197] Signal code:  (-6)
[pkrvmbietmlfzoi:63197] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8dd2845330]
[pkrvmbietmlfzoi:63197] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8dd289eb2c]
[pkrvmbietmlfzoi:63197] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8dd284527e]
[pkrvmbietmlfzoi:63197] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8dd28288ff]
[pkrvmbietmlfzoi:63197] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8dd2ca5ff5]
[pkrvmbietmlfzoi:63197] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8dd2cbb0da]
[pkrvmbietmlfzoi:63197] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8dd2ca5a55]
[pkrvmbietmlfzoi:63197] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8dd2ca5a6f]
[pkrvmbietmlfzoi:63197] [ 8] plumed_master(+0x146dd)[0x562c3c3396dd]
[pkrvmbietmlfzoi:63197] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8dd282a1ca]
[pkrvmbietmlfzoi:63197] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8dd282a28b]
[pkrvmbietmlfzoi:63197] [11] plumed_master(+0x15365)[0x562c3c33a365]
[pkrvmbietmlfzoi:63197] *** End of error message ***
</pre>
{% endraw %}
