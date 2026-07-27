**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmvrwv9:08001] *** Process received signal ***
[runnervmvrwv9:08001] Signal: Aborted (6)
[runnervmvrwv9:08001] Signal code:  (-6)
[runnervmvrwv9:08001] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f93a7445330]
[runnervmvrwv9:08001] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f93a749eb2c]
[runnervmvrwv9:08001] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f93a744527e]
[runnervmvrwv9:08001] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f93a74288ff]
[runnervmvrwv9:08001] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f93a78a5ff5]
[runnervmvrwv9:08001] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f93a78bb0da]
[runnervmvrwv9:08001] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f93a78a5a55]
[runnervmvrwv9:08001] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f93a78a5a6f]
[runnervmvrwv9:08001] [ 8] plumed_master(+0x146dd)[0x556614cf66dd]
[runnervmvrwv9:08001] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f93a742a1ca]
[runnervmvrwv9:08001] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f93a742a28b]
[runnervmvrwv9:08001] [11] plumed_master(+0x15365)[0x556614cf7365]
[runnervmvrwv9:08001] *** End of error message ***
</pre>
{% endraw %}
