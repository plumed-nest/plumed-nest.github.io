**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/trimer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[runnervmeorf1:04627] *** Process received signal ***
[runnervmeorf1:04627] Signal: Aborted (6)
[runnervmeorf1:04627] Signal code:  (-6)
[runnervmeorf1:04627] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3a12c45330]
[runnervmeorf1:04627] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3a12c9eb2c]
[runnervmeorf1:04627] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3a12c4527e]
[runnervmeorf1:04627] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3a12c288ff]
[runnervmeorf1:04627] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3a130a5ff5]
[runnervmeorf1:04627] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3a130bb0da]
[runnervmeorf1:04627] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3a130a5a55]
[runnervmeorf1:04627] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3a130a5a6f]
[runnervmeorf1:04627] [ 8] plumed_master(+0x146dd)[0x561fbb2f16dd]
[runnervmeorf1:04627] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3a12c2a1ca]
[runnervmeorf1:04627] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3a12c2a28b]
[runnervmeorf1:04627] [11] plumed_master(+0x15365)[0x561fbb2f2365]
[runnervmeorf1:04627] *** End of error message ***
</pre>
{% endraw %}
