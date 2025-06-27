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
[pkrvmbietmlfzoi:65823] *** Process received signal ***
[pkrvmbietmlfzoi:65823] Signal: Aborted (6)
[pkrvmbietmlfzoi:65823] Signal code:  (-6)
[pkrvmbietmlfzoi:65823] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc36d845330]
[pkrvmbietmlfzoi:65823] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc36d89eb2c]
[pkrvmbietmlfzoi:65823] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc36d84527e]
[pkrvmbietmlfzoi:65823] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc36d8288ff]
[pkrvmbietmlfzoi:65823] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc36dca5ff5]
[pkrvmbietmlfzoi:65823] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc36dcbb0da]
[pkrvmbietmlfzoi:65823] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc36dca5a55]
[pkrvmbietmlfzoi:65823] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc36dca5a6f]
[pkrvmbietmlfzoi:65823] [ 8] plumed_master(+0x146dd)[0x561409fe66dd]
[pkrvmbietmlfzoi:65823] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc36d82a1ca]
[pkrvmbietmlfzoi:65823] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc36d82a28b]
[pkrvmbietmlfzoi:65823] [11] plumed_master(+0x15365)[0x561409fe7365]
[pkrvmbietmlfzoi:65823] *** End of error message ***
</pre>
{% endraw %}
