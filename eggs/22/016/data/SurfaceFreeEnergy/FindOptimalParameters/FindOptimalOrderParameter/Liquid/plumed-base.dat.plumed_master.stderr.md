**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:08407] *** Process received signal ***
[pkrvmbietmlfzoi:08407] Signal: Aborted (6)
[pkrvmbietmlfzoi:08407] Signal code:  (-6)
[pkrvmbietmlfzoi:08407] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad03645330]
[pkrvmbietmlfzoi:08407] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad0369eb2c]
[pkrvmbietmlfzoi:08407] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad0364527e]
[pkrvmbietmlfzoi:08407] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad036288ff]
[pkrvmbietmlfzoi:08407] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad03aa5ff5]
[pkrvmbietmlfzoi:08407] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad03abb0da]
[pkrvmbietmlfzoi:08407] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad03aa5a55]
[pkrvmbietmlfzoi:08407] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad03aa5a6f]
[pkrvmbietmlfzoi:08407] [ 8] plumed_master(+0x146dd)[0x55aa0d1166dd]
[pkrvmbietmlfzoi:08407] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad0362a1ca]
[pkrvmbietmlfzoi:08407] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad0362a28b]
[pkrvmbietmlfzoi:08407] [11] plumed_master(+0x15365)[0x55aa0d117365]
[pkrvmbietmlfzoi:08407] *** End of error message ***
</pre>
{% endraw %}
