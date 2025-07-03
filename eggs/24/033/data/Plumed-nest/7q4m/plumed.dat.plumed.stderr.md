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
[pkrvmbietmlfzoi:06044] *** Process received signal ***
[pkrvmbietmlfzoi:06044] Signal: Aborted (6)
[pkrvmbietmlfzoi:06044] Signal code:  (-6)
[pkrvmbietmlfzoi:06044] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef73245330]
[pkrvmbietmlfzoi:06044] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef7329eb2c]
[pkrvmbietmlfzoi:06044] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef7324527e]
[pkrvmbietmlfzoi:06044] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef732288ff]
[pkrvmbietmlfzoi:06044] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef736a5ff5]
[pkrvmbietmlfzoi:06044] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef736bb0da]
[pkrvmbietmlfzoi:06044] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef736a5a55]
[pkrvmbietmlfzoi:06044] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef736a5a6f]
[pkrvmbietmlfzoi:06044] [ 8] plumed(+0x146dd)[0x55f01f8196dd]
[pkrvmbietmlfzoi:06044] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef7322a1ca]
[pkrvmbietmlfzoi:06044] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef7322a28b]
[pkrvmbietmlfzoi:06044] [11] plumed(+0x15365)[0x55f01f81a365]
[pkrvmbietmlfzoi:06044] *** End of error message ***
</pre>
{% endraw %}
