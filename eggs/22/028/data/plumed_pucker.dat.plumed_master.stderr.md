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
[pkrvmbietmlfzoi:08302] *** Process received signal ***
[pkrvmbietmlfzoi:08302] Signal: Aborted (6)
[pkrvmbietmlfzoi:08302] Signal code:  (-6)
[pkrvmbietmlfzoi:08302] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcbfda45330]
[pkrvmbietmlfzoi:08302] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcbfda9eb2c]
[pkrvmbietmlfzoi:08302] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcbfda4527e]
[pkrvmbietmlfzoi:08302] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcbfda288ff]
[pkrvmbietmlfzoi:08302] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcbfdea5ff5]
[pkrvmbietmlfzoi:08302] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcbfdebb0da]
[pkrvmbietmlfzoi:08302] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcbfdea5a55]
[pkrvmbietmlfzoi:08302] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcbfdea5a6f]
[pkrvmbietmlfzoi:08302] [ 8] plumed_master(+0x146dd)[0x55a8d141e6dd]
[pkrvmbietmlfzoi:08302] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcbfda2a1ca]
[pkrvmbietmlfzoi:08302] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcbfda2a28b]
[pkrvmbietmlfzoi:08302] [11] plumed_master(+0x15365)[0x55a8d141f365]
[pkrvmbietmlfzoi:08302] *** End of error message ***
</pre>
{% endraw %}
