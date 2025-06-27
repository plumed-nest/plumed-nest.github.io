**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:65746] *** Process received signal ***
[pkrvmbietmlfzoi:65746] Signal: Aborted (6)
[pkrvmbietmlfzoi:65746] Signal code:  (-6)
[pkrvmbietmlfzoi:65746] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbf0e645330]
[pkrvmbietmlfzoi:65746] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbf0e69eb2c]
[pkrvmbietmlfzoi:65746] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbf0e64527e]
[pkrvmbietmlfzoi:65746] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbf0e6288ff]
[pkrvmbietmlfzoi:65746] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbf0eaa5ff5]
[pkrvmbietmlfzoi:65746] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbf0eabb0da]
[pkrvmbietmlfzoi:65746] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbf0eaa5a55]
[pkrvmbietmlfzoi:65746] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbf0eaa5a6f]
[pkrvmbietmlfzoi:65746] [ 8] plumed_master(+0x146dd)[0x556299fba6dd]
[pkrvmbietmlfzoi:65746] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbf0e62a1ca]
[pkrvmbietmlfzoi:65746] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbf0e62a28b]
[pkrvmbietmlfzoi:65746] [11] plumed_master(+0x15365)[0x556299fbb365]
[pkrvmbietmlfzoi:65746] *** End of error message ***
</pre>
{% endraw %}
