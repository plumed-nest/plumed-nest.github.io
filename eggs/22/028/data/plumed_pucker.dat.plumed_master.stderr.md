**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvmbietmlfzoi:65178] *** Process received signal ***
[pkrvmbietmlfzoi:65178] Signal: Aborted (6)
[pkrvmbietmlfzoi:65178] Signal code:  (-6)
[pkrvmbietmlfzoi:65178] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2e25045330]
[pkrvmbietmlfzoi:65178] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2e2509eb2c]
[pkrvmbietmlfzoi:65178] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2e2504527e]
[pkrvmbietmlfzoi:65178] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2e250288ff]
[pkrvmbietmlfzoi:65178] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2e254a5ff5]
[pkrvmbietmlfzoi:65178] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2e254bb0da]
[pkrvmbietmlfzoi:65178] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2e254a5a55]
[pkrvmbietmlfzoi:65178] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2e254a5a6f]
[pkrvmbietmlfzoi:65178] [ 8] plumed_master(+0x146dd)[0x55f72abdb6dd]
[pkrvmbietmlfzoi:65178] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2e2502a1ca]
[pkrvmbietmlfzoi:65178] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2e2502a28b]
[pkrvmbietmlfzoi:65178] [11] plumed_master(+0x15365)[0x55f72abdc365]
[pkrvmbietmlfzoi:65178] *** End of error message ***
</pre>
{% endraw %}
