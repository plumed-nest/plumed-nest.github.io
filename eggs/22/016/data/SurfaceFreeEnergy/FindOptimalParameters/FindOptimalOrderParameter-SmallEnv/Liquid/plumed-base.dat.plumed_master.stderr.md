**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:65941] *** Process received signal ***
[pkrvmbietmlfzoi:65941] Signal: Aborted (6)
[pkrvmbietmlfzoi:65941] Signal code:  (-6)
[pkrvmbietmlfzoi:65941] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4794645330]
[pkrvmbietmlfzoi:65941] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f479469eb2c]
[pkrvmbietmlfzoi:65941] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f479464527e]
[pkrvmbietmlfzoi:65941] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f47946288ff]
[pkrvmbietmlfzoi:65941] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4794aa5ff5]
[pkrvmbietmlfzoi:65941] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4794abb0da]
[pkrvmbietmlfzoi:65941] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4794aa5a55]
[pkrvmbietmlfzoi:65941] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4794aa5a6f]
[pkrvmbietmlfzoi:65941] [ 8] plumed_master(+0x146dd)[0x5568d5ff36dd]
[pkrvmbietmlfzoi:65941] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f479462a1ca]
[pkrvmbietmlfzoi:65941] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f479462a28b]
[pkrvmbietmlfzoi:65941] [11] plumed_master(+0x15365)[0x5568d5ff4365]
[pkrvmbietmlfzoi:65941] *** End of error message ***
</pre>
{% endraw %}
