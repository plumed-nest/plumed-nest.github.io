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
[pkrvmbietmlfzoi:08485] *** Process received signal ***
[pkrvmbietmlfzoi:08485] Signal: Aborted (6)
[pkrvmbietmlfzoi:08485] Signal code:  (-6)
[pkrvmbietmlfzoi:08485] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc30d245330]
[pkrvmbietmlfzoi:08485] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc30d29eb2c]
[pkrvmbietmlfzoi:08485] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc30d24527e]
[pkrvmbietmlfzoi:08485] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc30d2288ff]
[pkrvmbietmlfzoi:08485] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc30d6a5ff5]
[pkrvmbietmlfzoi:08485] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc30d6bb0da]
[pkrvmbietmlfzoi:08485] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc30d6a5a55]
[pkrvmbietmlfzoi:08485] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc30d6a5a6f]
[pkrvmbietmlfzoi:08485] [ 8] plumed_master(+0x146dd)[0x55cf19a106dd]
[pkrvmbietmlfzoi:08485] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc30d22a1ca]
[pkrvmbietmlfzoi:08485] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc30d22a28b]
[pkrvmbietmlfzoi:08485] [11] plumed_master(+0x15365)[0x55cf19a11365]
[pkrvmbietmlfzoi:08485] *** End of error message ***
</pre>
{% endraw %}
