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
[pkrvmbietmlfzoi:63181] *** Process received signal ***
[pkrvmbietmlfzoi:63181] Signal: Aborted (6)
[pkrvmbietmlfzoi:63181] Signal code:  (-6)
[pkrvmbietmlfzoi:63181] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e5dc45330]
[pkrvmbietmlfzoi:63181] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e5dc9eb2c]
[pkrvmbietmlfzoi:63181] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e5dc4527e]
[pkrvmbietmlfzoi:63181] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e5dc288ff]
[pkrvmbietmlfzoi:63181] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e5e0a5ff5]
[pkrvmbietmlfzoi:63181] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e5e0bb0da]
[pkrvmbietmlfzoi:63181] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e5e0a5a55]
[pkrvmbietmlfzoi:63181] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e5e0a5a6f]
[pkrvmbietmlfzoi:63181] [ 8] plumed(+0x146dd)[0x5579b29296dd]
[pkrvmbietmlfzoi:63181] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e5dc2a1ca]
[pkrvmbietmlfzoi:63181] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e5dc2a28b]
[pkrvmbietmlfzoi:63181] [11] plumed(+0x15365)[0x5579b292a365]
[pkrvmbietmlfzoi:63181] *** End of error message ***
</pre>
{% endraw %}
