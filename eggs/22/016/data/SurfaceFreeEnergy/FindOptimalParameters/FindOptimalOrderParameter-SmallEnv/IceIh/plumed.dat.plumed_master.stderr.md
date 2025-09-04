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
[pkrvm7jw40e0xgp:10621] *** Process received signal ***
[pkrvm7jw40e0xgp:10621] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10621] Signal code:  (-6)
[pkrvm7jw40e0xgp:10621] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2234c45330]
[pkrvm7jw40e0xgp:10621] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2234c9eb2c]
[pkrvm7jw40e0xgp:10621] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2234c4527e]
[pkrvm7jw40e0xgp:10621] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2234c288ff]
[pkrvm7jw40e0xgp:10621] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f22350a5ff5]
[pkrvm7jw40e0xgp:10621] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f22350bb0da]
[pkrvm7jw40e0xgp:10621] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f22350a5a55]
[pkrvm7jw40e0xgp:10621] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f22350a5a6f]
[pkrvm7jw40e0xgp:10621] [ 8] plumed_master(+0x146dd)[0x5600ce86b6dd]
[pkrvm7jw40e0xgp:10621] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2234c2a1ca]
[pkrvm7jw40e0xgp:10621] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2234c2a28b]
[pkrvm7jw40e0xgp:10621] [11] plumed_master(+0x15365)[0x5600ce86c365]
[pkrvm7jw40e0xgp:10621] *** End of error message ***
</pre>
{% endraw %}
