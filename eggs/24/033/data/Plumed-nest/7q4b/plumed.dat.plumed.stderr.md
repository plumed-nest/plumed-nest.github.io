**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmbietmlfzoi:62301] *** Process received signal ***
[pkrvmbietmlfzoi:62301] Signal: Aborted (6)
[pkrvmbietmlfzoi:62301] Signal code:  (-6)
[pkrvmbietmlfzoi:62301] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3c02c45330]
[pkrvmbietmlfzoi:62301] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3c02c9eb2c]
[pkrvmbietmlfzoi:62301] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3c02c4527e]
[pkrvmbietmlfzoi:62301] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3c02c288ff]
[pkrvmbietmlfzoi:62301] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3c030a5ff5]
[pkrvmbietmlfzoi:62301] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3c030bb0da]
[pkrvmbietmlfzoi:62301] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3c030a5a55]
[pkrvmbietmlfzoi:62301] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3c030a5a6f]
[pkrvmbietmlfzoi:62301] [ 8] plumed(+0x146dd)[0x557a093416dd]
[pkrvmbietmlfzoi:62301] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3c02c2a1ca]
[pkrvmbietmlfzoi:62301] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3c02c2a28b]
[pkrvmbietmlfzoi:62301] [11] plumed(+0x15365)[0x557a09342365]
[pkrvmbietmlfzoi:62301] *** End of error message ***
</pre>
{% endraw %}
