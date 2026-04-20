**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/pentamer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @41 : keyword ARG is compulsory for this action
[runnervmeorf1:04549] *** Process received signal ***
[runnervmeorf1:04549] Signal: Aborted (6)
[runnervmeorf1:04549] Signal code:  (-6)
[runnervmeorf1:04549] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f162cc45330]
[runnervmeorf1:04549] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f162cc9eb2c]
[runnervmeorf1:04549] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f162cc4527e]
[runnervmeorf1:04549] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f162cc288ff]
[runnervmeorf1:04549] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f162d0a5ff5]
[runnervmeorf1:04549] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f162d0bb0da]
[runnervmeorf1:04549] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f162d0a5a55]
[runnervmeorf1:04549] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f162d0a5a6f]
[runnervmeorf1:04549] [ 8] plumed_master(+0x146dd)[0x564d7b43a6dd]
[runnervmeorf1:04549] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f162cc2a1ca]
[runnervmeorf1:04549] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f162cc2a28b]
[runnervmeorf1:04549] [11] plumed_master(+0x15365)[0x564d7b43b365]
[runnervmeorf1:04549] *** End of error message ***
</pre>
{% endraw %}
