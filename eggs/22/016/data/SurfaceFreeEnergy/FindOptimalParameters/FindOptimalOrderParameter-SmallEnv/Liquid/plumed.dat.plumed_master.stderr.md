**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az1781-845:62602] *** Process received signal ***
[fv-az1781-845:62602] Signal: Aborted (6)
[fv-az1781-845:62602] Signal code:  (-6)
[fv-az1781-845:62602] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6c50a45330]
[fv-az1781-845:62602] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6c50a9eb2c]
[fv-az1781-845:62602] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6c50a4527e]
[fv-az1781-845:62602] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6c50a288ff]
[fv-az1781-845:62602] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6c50ea5ff5]
[fv-az1781-845:62602] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6c50ebb0da]
[fv-az1781-845:62602] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6c50ea5a55]
[fv-az1781-845:62602] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6c50ea5a6f]
[fv-az1781-845:62602] [ 8] plumed_master(+0x146dd)[0x557977c4d6dd]
[fv-az1781-845:62602] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6c50a2a1ca]
[fv-az1781-845:62602] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6c50a2a28b]
[fv-az1781-845:62602] [11] plumed_master(+0x15365)[0x557977c4e365]
[fv-az1781-845:62602] *** End of error message ***
</pre>
{% endraw %}
