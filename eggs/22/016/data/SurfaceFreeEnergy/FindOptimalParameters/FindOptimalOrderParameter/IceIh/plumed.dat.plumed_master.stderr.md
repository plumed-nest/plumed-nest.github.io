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
[pkrvmbietmlfzoi:08367] *** Process received signal ***
[pkrvmbietmlfzoi:08367] Signal: Aborted (6)
[pkrvmbietmlfzoi:08367] Signal code:  (-6)
[pkrvmbietmlfzoi:08367] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa2e1645330]
[pkrvmbietmlfzoi:08367] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa2e169eb2c]
[pkrvmbietmlfzoi:08367] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa2e164527e]
[pkrvmbietmlfzoi:08367] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa2e16288ff]
[pkrvmbietmlfzoi:08367] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa2e1aa5ff5]
[pkrvmbietmlfzoi:08367] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa2e1abb0da]
[pkrvmbietmlfzoi:08367] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa2e1aa5a55]
[pkrvmbietmlfzoi:08367] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa2e1aa5a6f]
[pkrvmbietmlfzoi:08367] [ 8] plumed_master(+0x146dd)[0x55e1b30766dd]
[pkrvmbietmlfzoi:08367] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa2e162a1ca]
[pkrvmbietmlfzoi:08367] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa2e162a28b]
[pkrvmbietmlfzoi:08367] [11] plumed_master(+0x15365)[0x55e1b3077365]
[pkrvmbietmlfzoi:08367] *** End of error message ***
</pre>
{% endraw %}
