**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[pkrvmbietmlfzoi:10891] *** Process received signal ***
[pkrvmbietmlfzoi:10891] Signal: Aborted (6)
[pkrvmbietmlfzoi:10891] Signal code:  (-6)
[pkrvmbietmlfzoi:10891] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc1c6245330]
[pkrvmbietmlfzoi:10891] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc1c629eb2c]
[pkrvmbietmlfzoi:10891] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc1c624527e]
[pkrvmbietmlfzoi:10891] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc1c62288ff]
[pkrvmbietmlfzoi:10891] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc1c66a5ff5]
[pkrvmbietmlfzoi:10891] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc1c66bb0da]
[pkrvmbietmlfzoi:10891] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc1c66a5a55]
[pkrvmbietmlfzoi:10891] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc1c66a5a6f]
[pkrvmbietmlfzoi:10891] [ 8] plumed_master(+0x146dd)[0x55608a4f06dd]
[pkrvmbietmlfzoi:10891] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc1c622a1ca]
[pkrvmbietmlfzoi:10891] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc1c622a28b]
[pkrvmbietmlfzoi:10891] [11] plumed_master(+0x15365)[0x55608a4f1365]
[pkrvmbietmlfzoi:10891] *** End of error message ***
</pre>
{% endraw %}
