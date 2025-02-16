**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az1781-845:62411] *** Process received signal ***
[fv-az1781-845:62411] Signal: Aborted (6)
[fv-az1781-845:62411] Signal code:  (-6)
[fv-az1781-845:62411] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5e82845330]
[fv-az1781-845:62411] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5e8289eb2c]
[fv-az1781-845:62411] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5e8284527e]
[fv-az1781-845:62411] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5e828288ff]
[fv-az1781-845:62411] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5e82ca5ff5]
[fv-az1781-845:62411] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5e82cbb0da]
[fv-az1781-845:62411] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5e82ca5a55]
[fv-az1781-845:62411] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5e82ca5a6f]
[fv-az1781-845:62411] [ 8] plumed_master(+0x146dd)[0x5586203606dd]
[fv-az1781-845:62411] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5e8282a1ca]
[fv-az1781-845:62411] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5e8282a28b]
[fv-az1781-845:62411] [11] plumed_master(+0x15365)[0x558620361365]
[fv-az1781-845:62411] *** End of error message ***
</pre>
{% endraw %}
