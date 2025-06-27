**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[pkrvmbietmlfzoi:69171] *** Process received signal ***
[pkrvmbietmlfzoi:69171] Signal: Aborted (6)
[pkrvmbietmlfzoi:69171] Signal code:  (-6)
[pkrvmbietmlfzoi:69171] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda4e645330]
[pkrvmbietmlfzoi:69171] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda4e69eb2c]
[pkrvmbietmlfzoi:69171] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda4e64527e]
[pkrvmbietmlfzoi:69171] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda4e6288ff]
[pkrvmbietmlfzoi:69171] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda4eaa5ff5]
[pkrvmbietmlfzoi:69171] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda4eabb0da]
[pkrvmbietmlfzoi:69171] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda4eaa5a55]
[pkrvmbietmlfzoi:69171] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda4eaa5a6f]
[pkrvmbietmlfzoi:69171] [ 8] plumed(+0x146dd)[0x5606325786dd]
[pkrvmbietmlfzoi:69171] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda4e62a1ca]
[pkrvmbietmlfzoi:69171] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda4e62a28b]
[pkrvmbietmlfzoi:69171] [11] plumed(+0x15365)[0x560632579365]
[pkrvmbietmlfzoi:69171] *** End of error message ***
</pre>
{% endraw %}
