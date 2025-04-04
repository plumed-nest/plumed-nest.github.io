**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az2207-973:07803] *** Process received signal ***
[fv-az2207-973:07803] Signal: Aborted (6)
[fv-az2207-973:07803] Signal code:  (-6)
[fv-az2207-973:07803] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd920245330]
[fv-az2207-973:07803] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd92029eb2c]
[fv-az2207-973:07803] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd92024527e]
[fv-az2207-973:07803] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd9202288ff]
[fv-az2207-973:07803] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd9206a5ff5]
[fv-az2207-973:07803] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd9206bb0da]
[fv-az2207-973:07803] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd9206a5a55]
[fv-az2207-973:07803] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd9206a5a6f]
[fv-az2207-973:07803] [ 8] plumed_master(+0x146dd)[0x565494d976dd]
[fv-az2207-973:07803] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd92022a1ca]
[fv-az2207-973:07803] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd92022a28b]
[fv-az2207-973:07803] [11] plumed_master(+0x15365)[0x565494d98365]
[fv-az2207-973:07803] *** End of error message ***
</pre>
{% endraw %}
