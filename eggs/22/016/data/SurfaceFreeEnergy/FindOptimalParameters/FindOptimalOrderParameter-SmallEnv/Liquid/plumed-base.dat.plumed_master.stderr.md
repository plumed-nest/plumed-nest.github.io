**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az2207-973:08004] *** Process received signal ***
[fv-az2207-973:08004] Signal: Aborted (6)
[fv-az2207-973:08004] Signal code:  (-6)
[fv-az2207-973:08004] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1abca45330]
[fv-az2207-973:08004] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1abca9eb2c]
[fv-az2207-973:08004] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1abca4527e]
[fv-az2207-973:08004] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1abca288ff]
[fv-az2207-973:08004] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1abcea5ff5]
[fv-az2207-973:08004] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1abcebb0da]
[fv-az2207-973:08004] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1abcea5a55]
[fv-az2207-973:08004] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1abcea5a6f]
[fv-az2207-973:08004] [ 8] plumed_master(+0x146dd)[0x555dbb8986dd]
[fv-az2207-973:08004] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1abca2a1ca]
[fv-az2207-973:08004] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1abca2a28b]
[fv-az2207-973:08004] [11] plumed_master(+0x15365)[0x555dbb899365]
[fv-az2207-973:08004] *** End of error message ***
</pre>
{% endraw %}
