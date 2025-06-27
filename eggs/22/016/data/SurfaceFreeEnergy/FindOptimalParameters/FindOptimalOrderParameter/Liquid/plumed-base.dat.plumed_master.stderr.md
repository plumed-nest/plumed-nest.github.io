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
[pkrvmbietmlfzoi:65785] *** Process received signal ***
[pkrvmbietmlfzoi:65785] Signal: Aborted (6)
[pkrvmbietmlfzoi:65785] Signal code:  (-6)
[pkrvmbietmlfzoi:65785] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4494045330]
[pkrvmbietmlfzoi:65785] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f449409eb2c]
[pkrvmbietmlfzoi:65785] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f449404527e]
[pkrvmbietmlfzoi:65785] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f44940288ff]
[pkrvmbietmlfzoi:65785] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f44944a5ff5]
[pkrvmbietmlfzoi:65785] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f44944bb0da]
[pkrvmbietmlfzoi:65785] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f44944a5a55]
[pkrvmbietmlfzoi:65785] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f44944a5a6f]
[pkrvmbietmlfzoi:65785] [ 8] plumed_master(+0x146dd)[0x561b7eccc6dd]
[pkrvmbietmlfzoi:65785] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f449402a1ca]
[pkrvmbietmlfzoi:65785] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f449402a28b]
[pkrvmbietmlfzoi:65785] [11] plumed_master(+0x15365)[0x561b7eccd365]
[pkrvmbietmlfzoi:65785] *** End of error message ***
</pre>
{% endraw %}
