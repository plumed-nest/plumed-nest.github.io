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
[pkrvmpptgkbjq6m:10493] *** Process received signal ***
[pkrvmpptgkbjq6m:10493] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10493] Signal code:  (-6)
[pkrvmpptgkbjq6m:10493] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7150a45330]
[pkrvmpptgkbjq6m:10493] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7150a9eb2c]
[pkrvmpptgkbjq6m:10493] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7150a4527e]
[pkrvmpptgkbjq6m:10493] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7150a288ff]
[pkrvmpptgkbjq6m:10493] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7150ea5ff5]
[pkrvmpptgkbjq6m:10493] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7150ebb0da]
[pkrvmpptgkbjq6m:10493] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7150ea5a55]
[pkrvmpptgkbjq6m:10493] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7150ea5a6f]
[pkrvmpptgkbjq6m:10493] [ 8] plumed_master(+0x146dd)[0x562ef99c66dd]
[pkrvmpptgkbjq6m:10493] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7150a2a1ca]
[pkrvmpptgkbjq6m:10493] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7150a2a28b]
[pkrvmpptgkbjq6m:10493] [11] plumed_master(+0x15365)[0x562ef99c7365]
[pkrvmpptgkbjq6m:10493] *** End of error message ***
</pre>
{% endraw %}
