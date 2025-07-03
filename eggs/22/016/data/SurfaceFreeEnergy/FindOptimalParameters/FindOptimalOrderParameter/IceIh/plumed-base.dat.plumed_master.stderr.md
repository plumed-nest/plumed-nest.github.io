**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:08329] *** Process received signal ***
[pkrvmbietmlfzoi:08329] Signal: Aborted (6)
[pkrvmbietmlfzoi:08329] Signal code:  (-6)
[pkrvmbietmlfzoi:08329] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f745b045330]
[pkrvmbietmlfzoi:08329] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f745b09eb2c]
[pkrvmbietmlfzoi:08329] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f745b04527e]
[pkrvmbietmlfzoi:08329] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f745b0288ff]
[pkrvmbietmlfzoi:08329] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f745b4a5ff5]
[pkrvmbietmlfzoi:08329] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f745b4bb0da]
[pkrvmbietmlfzoi:08329] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f745b4a5a55]
[pkrvmbietmlfzoi:08329] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f745b4a5a6f]
[pkrvmbietmlfzoi:08329] [ 8] plumed_master(+0x146dd)[0x5559684896dd]
[pkrvmbietmlfzoi:08329] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f745b02a1ca]
[pkrvmbietmlfzoi:08329] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f745b02a28b]
[pkrvmbietmlfzoi:08329] [11] plumed_master(+0x15365)[0x55596848a365]
[pkrvmbietmlfzoi:08329] *** End of error message ***
</pre>
{% endraw %}
