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
[pkrvmbietmlfzoi:10311] *** Process received signal ***
[pkrvmbietmlfzoi:10311] Signal: Aborted (6)
[pkrvmbietmlfzoi:10311] Signal code:  (-6)
[pkrvmbietmlfzoi:10311] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdb76445330]
[pkrvmbietmlfzoi:10311] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdb7649eb2c]
[pkrvmbietmlfzoi:10311] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdb7644527e]
[pkrvmbietmlfzoi:10311] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdb764288ff]
[pkrvmbietmlfzoi:10311] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdb768a5ff5]
[pkrvmbietmlfzoi:10311] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdb768bb0da]
[pkrvmbietmlfzoi:10311] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdb768a5a55]
[pkrvmbietmlfzoi:10311] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdb768a5a6f]
[pkrvmbietmlfzoi:10311] [ 8] plumed_master(+0x146dd)[0x560eaacbc6dd]
[pkrvmbietmlfzoi:10311] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdb7642a1ca]
[pkrvmbietmlfzoi:10311] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdb7642a28b]
[pkrvmbietmlfzoi:10311] [11] plumed_master(+0x15365)[0x560eaacbd365]
[pkrvmbietmlfzoi:10311] *** End of error message ***
</pre>
{% endraw %}
