**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:65863] *** Process received signal ***
[pkrvmbietmlfzoi:65863] Signal: Aborted (6)
[pkrvmbietmlfzoi:65863] Signal code:  (-6)
[pkrvmbietmlfzoi:65863] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc2c9445330]
[pkrvmbietmlfzoi:65863] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc2c949eb2c]
[pkrvmbietmlfzoi:65863] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc2c944527e]
[pkrvmbietmlfzoi:65863] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc2c94288ff]
[pkrvmbietmlfzoi:65863] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc2c98a5ff5]
[pkrvmbietmlfzoi:65863] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc2c98bb0da]
[pkrvmbietmlfzoi:65863] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc2c98a5a55]
[pkrvmbietmlfzoi:65863] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc2c98a5a6f]
[pkrvmbietmlfzoi:65863] [ 8] plumed_master(+0x146dd)[0x55d3b8bc46dd]
[pkrvmbietmlfzoi:65863] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc2c942a1ca]
[pkrvmbietmlfzoi:65863] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc2c942a28b]
[pkrvmbietmlfzoi:65863] [11] plumed_master(+0x15365)[0x55d3b8bc5365]
[pkrvmbietmlfzoi:65863] *** End of error message ***
</pre>
{% endraw %}
