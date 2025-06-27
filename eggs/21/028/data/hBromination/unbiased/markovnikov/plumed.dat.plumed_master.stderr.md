**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvmbietmlfzoi:67602] *** Process received signal ***
[pkrvmbietmlfzoi:67602] Signal: Aborted (6)
[pkrvmbietmlfzoi:67602] Signal code:  (-6)
[pkrvmbietmlfzoi:67602] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2a57c45330]
[pkrvmbietmlfzoi:67602] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2a57c9eb2c]
[pkrvmbietmlfzoi:67602] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2a57c4527e]
[pkrvmbietmlfzoi:67602] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2a57c288ff]
[pkrvmbietmlfzoi:67602] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2a580a5ff5]
[pkrvmbietmlfzoi:67602] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2a580bb0da]
[pkrvmbietmlfzoi:67602] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2a580a5a55]
[pkrvmbietmlfzoi:67602] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2a580a5a6f]
[pkrvmbietmlfzoi:67602] [ 8] plumed_master(+0x146dd)[0x55b59ef366dd]
[pkrvmbietmlfzoi:67602] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2a57c2a1ca]
[pkrvmbietmlfzoi:67602] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2a57c2a28b]
[pkrvmbietmlfzoi:67602] [11] plumed_master(+0x15365)[0x55b59ef37365]
[pkrvmbietmlfzoi:67602] *** End of error message ***
</pre>
{% endraw %}
