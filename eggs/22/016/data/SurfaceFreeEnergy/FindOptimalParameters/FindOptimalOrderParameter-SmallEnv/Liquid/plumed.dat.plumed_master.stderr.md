**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:10613] *** Process received signal ***
[pkrvmpptgkbjq6m:10613] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10613] Signal code:  (-6)
[pkrvmpptgkbjq6m:10613] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd9a4245330]
[pkrvmpptgkbjq6m:10613] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd9a429eb2c]
[pkrvmpptgkbjq6m:10613] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd9a424527e]
[pkrvmpptgkbjq6m:10613] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd9a42288ff]
[pkrvmpptgkbjq6m:10613] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd9a46a5ff5]
[pkrvmpptgkbjq6m:10613] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd9a46bb0da]
[pkrvmpptgkbjq6m:10613] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd9a46a5a55]
[pkrvmpptgkbjq6m:10613] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd9a46a5a6f]
[pkrvmpptgkbjq6m:10613] [ 8] plumed_master(+0x146dd)[0x5644381866dd]
[pkrvmpptgkbjq6m:10613] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd9a422a1ca]
[pkrvmpptgkbjq6m:10613] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd9a422a28b]
[pkrvmpptgkbjq6m:10613] [11] plumed_master(+0x15365)[0x564438187365]
[pkrvmpptgkbjq6m:10613] *** End of error message ***
</pre>
{% endraw %}
