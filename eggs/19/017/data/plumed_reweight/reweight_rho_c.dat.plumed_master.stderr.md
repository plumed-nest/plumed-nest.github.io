**Project ID:** [plumID:19.017]({{ '/' | absolute_url }}eggs/19/017/)  
Stderr for source:  plumed_reweight/reweight_rho_c.dat   
Download: [zipped raw stdout](reweight_rho_c.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_c.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:13403] *** Process received signal ***
[pkrvmbietmlfzoi:13403] Signal: Aborted (6)
[pkrvmbietmlfzoi:13403] Signal code:  (-6)
[pkrvmbietmlfzoi:13403] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f30f4a45330]
[pkrvmbietmlfzoi:13403] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f30f4a9eb2c]
[pkrvmbietmlfzoi:13403] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f30f4a4527e]
[pkrvmbietmlfzoi:13403] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f30f4a288ff]
[pkrvmbietmlfzoi:13403] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f30f4ea5ff5]
[pkrvmbietmlfzoi:13403] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f30f4ebb0da]
[pkrvmbietmlfzoi:13403] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f30f4ea5a55]
[pkrvmbietmlfzoi:13403] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f30f4ea5a6f]
[pkrvmbietmlfzoi:13403] [ 8] plumed_master(+0x146dd)[0x563a0a9876dd]
[pkrvmbietmlfzoi:13403] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f30f4a2a1ca]
[pkrvmbietmlfzoi:13403] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f30f4a2a28b]
[pkrvmbietmlfzoi:13403] [11] plumed_master(+0x15365)[0x563a0a988365]
[pkrvmbietmlfzoi:13403] *** End of error message ***
</pre>
{% endraw %}
