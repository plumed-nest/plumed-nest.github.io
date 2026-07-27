**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmvrwv9:07963] *** Process received signal ***
[runnervmvrwv9:07963] Signal: Aborted (6)
[runnervmvrwv9:07963] Signal code:  (-6)
[runnervmvrwv9:07963] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f16f5245330]
[runnervmvrwv9:07963] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f16f529eb2c]
[runnervmvrwv9:07963] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f16f524527e]
[runnervmvrwv9:07963] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f16f52288ff]
[runnervmvrwv9:07963] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f16f56a5ff5]
[runnervmvrwv9:07963] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f16f56bb0da]
[runnervmvrwv9:07963] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f16f56a5a55]
[runnervmvrwv9:07963] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f16f56a5a6f]
[runnervmvrwv9:07963] [ 8] plumed_master(+0x146dd)[0x56198f3666dd]
[runnervmvrwv9:07963] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f16f522a1ca]
[runnervmvrwv9:07963] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f16f522a28b]
[runnervmvrwv9:07963] [11] plumed_master(+0x15365)[0x56198f367365]
[runnervmvrwv9:07963] *** End of error message ***
</pre>
{% endraw %}
