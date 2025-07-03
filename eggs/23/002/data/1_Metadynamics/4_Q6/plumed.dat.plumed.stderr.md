**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[pkrvmbietmlfzoi:08602] *** Process received signal ***
[pkrvmbietmlfzoi:08602] Signal: Aborted (6)
[pkrvmbietmlfzoi:08602] Signal code:  (-6)
[pkrvmbietmlfzoi:08602] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc6c4045330]
[pkrvmbietmlfzoi:08602] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc6c409eb2c]
[pkrvmbietmlfzoi:08602] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc6c404527e]
[pkrvmbietmlfzoi:08602] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6c40288ff]
[pkrvmbietmlfzoi:08602] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6c44a5ff5]
[pkrvmbietmlfzoi:08602] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6c44bb0da]
[pkrvmbietmlfzoi:08602] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6c44a5a55]
[pkrvmbietmlfzoi:08602] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6c44a5a6f]
[pkrvmbietmlfzoi:08602] [ 8] plumed(+0x146dd)[0x5571a9b146dd]
[pkrvmbietmlfzoi:08602] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc6c402a1ca]
[pkrvmbietmlfzoi:08602] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc6c402a28b]
[pkrvmbietmlfzoi:08602] [11] plumed(+0x15365)[0x5571a9b15365]
[pkrvmbietmlfzoi:08602] *** End of error message ***
</pre>
{% endraw %}
