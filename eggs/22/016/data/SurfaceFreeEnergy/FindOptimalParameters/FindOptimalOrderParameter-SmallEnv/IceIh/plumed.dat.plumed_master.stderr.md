**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:08526] *** Process received signal ***
[pkrvmbietmlfzoi:08526] Signal: Aborted (6)
[pkrvmbietmlfzoi:08526] Signal code:  (-6)
[pkrvmbietmlfzoi:08526] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fba23a45330]
[pkrvmbietmlfzoi:08526] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fba23a9eb2c]
[pkrvmbietmlfzoi:08526] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fba23a4527e]
[pkrvmbietmlfzoi:08526] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fba23a288ff]
[pkrvmbietmlfzoi:08526] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fba23ea5ff5]
[pkrvmbietmlfzoi:08526] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fba23ebb0da]
[pkrvmbietmlfzoi:08526] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fba23ea5a55]
[pkrvmbietmlfzoi:08526] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fba23ea5a6f]
[pkrvmbietmlfzoi:08526] [ 8] plumed_master(+0x146dd)[0x5606423e16dd]
[pkrvmbietmlfzoi:08526] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fba23a2a1ca]
[pkrvmbietmlfzoi:08526] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fba23a2a28b]
[pkrvmbietmlfzoi:08526] [11] plumed_master(+0x15365)[0x5606423e2365]
[pkrvmbietmlfzoi:08526] *** End of error message ***
</pre>
{% endraw %}
