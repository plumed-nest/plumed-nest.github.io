**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmbietmlfzoi:06076] *** Process received signal ***
[pkrvmbietmlfzoi:06076] Signal: Aborted (6)
[pkrvmbietmlfzoi:06076] Signal code:  (-6)
[pkrvmbietmlfzoi:06076] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f815fc45330]
[pkrvmbietmlfzoi:06076] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f815fc9eb2c]
[pkrvmbietmlfzoi:06076] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f815fc4527e]
[pkrvmbietmlfzoi:06076] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f815fc288ff]
[pkrvmbietmlfzoi:06076] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f81600a5ff5]
[pkrvmbietmlfzoi:06076] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f81600bb0da]
[pkrvmbietmlfzoi:06076] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f81600a5a55]
[pkrvmbietmlfzoi:06076] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f81600a5a6f]
[pkrvmbietmlfzoi:06076] [ 8] plumed_master(+0x146dd)[0x5559c19cd6dd]
[pkrvmbietmlfzoi:06076] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f815fc2a1ca]
[pkrvmbietmlfzoi:06076] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f815fc2a28b]
[pkrvmbietmlfzoi:06076] [11] plumed_master(+0x15365)[0x5559c19ce365]
[pkrvmbietmlfzoi:06076] *** End of error message ***
</pre>
{% endraw %}
