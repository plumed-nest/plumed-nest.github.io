**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmbietmlfzoi:62452] *** Process received signal ***
[pkrvmbietmlfzoi:62452] Signal: Aborted (6)
[pkrvmbietmlfzoi:62452] Signal code:  (-6)
[pkrvmbietmlfzoi:62452] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f616c445330]
[pkrvmbietmlfzoi:62452] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f616c49eb2c]
[pkrvmbietmlfzoi:62452] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f616c44527e]
[pkrvmbietmlfzoi:62452] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f616c4288ff]
[pkrvmbietmlfzoi:62452] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f616c8a5ff5]
[pkrvmbietmlfzoi:62452] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f616c8bb0da]
[pkrvmbietmlfzoi:62452] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f616c8a5a55]
[pkrvmbietmlfzoi:62452] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f616c8a5a6f]
[pkrvmbietmlfzoi:62452] [ 8] plumed(+0x146dd)[0x55c6e4bcb6dd]
[pkrvmbietmlfzoi:62452] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f616c42a1ca]
[pkrvmbietmlfzoi:62452] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f616c42a28b]
[pkrvmbietmlfzoi:62452] [11] plumed(+0x15365)[0x55c6e4bcc365]
[pkrvmbietmlfzoi:62452] *** End of error message ***
</pre>
{% endraw %}
