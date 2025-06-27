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
[pkrvmbietmlfzoi:62468] *** Process received signal ***
[pkrvmbietmlfzoi:62468] Signal: Aborted (6)
[pkrvmbietmlfzoi:62468] Signal code:  (-6)
[pkrvmbietmlfzoi:62468] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3cac645330]
[pkrvmbietmlfzoi:62468] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3cac69eb2c]
[pkrvmbietmlfzoi:62468] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3cac64527e]
[pkrvmbietmlfzoi:62468] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3cac6288ff]
[pkrvmbietmlfzoi:62468] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3cacaa5ff5]
[pkrvmbietmlfzoi:62468] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3cacabb0da]
[pkrvmbietmlfzoi:62468] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3cacaa5a55]
[pkrvmbietmlfzoi:62468] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3cacaa5a6f]
[pkrvmbietmlfzoi:62468] [ 8] plumed_master(+0x146dd)[0x55943fb986dd]
[pkrvmbietmlfzoi:62468] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3cac62a1ca]
[pkrvmbietmlfzoi:62468] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3cac62a28b]
[pkrvmbietmlfzoi:62468] [11] plumed_master(+0x15365)[0x55943fb99365]
[pkrvmbietmlfzoi:62468] *** End of error message ***
</pre>
{% endraw %}
