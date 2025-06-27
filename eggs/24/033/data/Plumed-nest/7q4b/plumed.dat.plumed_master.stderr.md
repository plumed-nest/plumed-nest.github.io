**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmbietmlfzoi:62317] *** Process received signal ***
[pkrvmbietmlfzoi:62317] Signal: Aborted (6)
[pkrvmbietmlfzoi:62317] Signal code:  (-6)
[pkrvmbietmlfzoi:62317] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7172845330]
[pkrvmbietmlfzoi:62317] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f717289eb2c]
[pkrvmbietmlfzoi:62317] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f717284527e]
[pkrvmbietmlfzoi:62317] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71728288ff]
[pkrvmbietmlfzoi:62317] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7172ca5ff5]
[pkrvmbietmlfzoi:62317] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7172cbb0da]
[pkrvmbietmlfzoi:62317] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7172ca5a55]
[pkrvmbietmlfzoi:62317] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7172ca5a6f]
[pkrvmbietmlfzoi:62317] [ 8] plumed_master(+0x146dd)[0x5647d06f16dd]
[pkrvmbietmlfzoi:62317] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f717282a1ca]
[pkrvmbietmlfzoi:62317] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f717282a28b]
[pkrvmbietmlfzoi:62317] [11] plumed_master(+0x15365)[0x5647d06f2365]
[pkrvmbietmlfzoi:62317] *** End of error message ***
</pre>
{% endraw %}
