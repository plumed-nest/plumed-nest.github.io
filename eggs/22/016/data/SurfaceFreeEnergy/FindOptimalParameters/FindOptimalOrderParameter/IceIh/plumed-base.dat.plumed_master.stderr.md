**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az1781-845:62332] *** Process received signal ***
[fv-az1781-845:62332] Signal: Aborted (6)
[fv-az1781-845:62332] Signal code:  (-6)
[fv-az1781-845:62332] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa55ac45330]
[fv-az1781-845:62332] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa55ac9eb2c]
[fv-az1781-845:62332] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa55ac4527e]
[fv-az1781-845:62332] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa55ac288ff]
[fv-az1781-845:62332] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa55b0a5ff5]
[fv-az1781-845:62332] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa55b0bb0da]
[fv-az1781-845:62332] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa55b0a5a55]
[fv-az1781-845:62332] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa55b0a5a6f]
[fv-az1781-845:62332] [ 8] plumed_master(+0x146dd)[0x55b4f5b816dd]
[fv-az1781-845:62332] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa55ac2a1ca]
[fv-az1781-845:62332] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa55ac2a28b]
[fv-az1781-845:62332] [11] plumed_master(+0x15365)[0x55b4f5b82365]
[fv-az1781-845:62332] *** End of error message ***
</pre>
{% endraw %}
