**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:08446] *** Process received signal ***
[pkrvmbietmlfzoi:08446] Signal: Aborted (6)
[pkrvmbietmlfzoi:08446] Signal code:  (-6)
[pkrvmbietmlfzoi:08446] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe33f245330]
[pkrvmbietmlfzoi:08446] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe33f29eb2c]
[pkrvmbietmlfzoi:08446] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe33f24527e]
[pkrvmbietmlfzoi:08446] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe33f2288ff]
[pkrvmbietmlfzoi:08446] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe33f6a5ff5]
[pkrvmbietmlfzoi:08446] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe33f6bb0da]
[pkrvmbietmlfzoi:08446] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe33f6a5a55]
[pkrvmbietmlfzoi:08446] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe33f6a5a6f]
[pkrvmbietmlfzoi:08446] [ 8] plumed_master(+0x146dd)[0x556d1e5ae6dd]
[pkrvmbietmlfzoi:08446] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe33f22a1ca]
[pkrvmbietmlfzoi:08446] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe33f22a28b]
[pkrvmbietmlfzoi:08446] [11] plumed_master(+0x15365)[0x556d1e5af365]
[pkrvmbietmlfzoi:08446] *** End of error message ***
</pre>
{% endraw %}
