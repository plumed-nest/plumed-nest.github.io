**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/monomer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @27 : keyword ARG is compulsory for this action
[runnervmeorf1:04510] *** Process received signal ***
[runnervmeorf1:04510] Signal: Aborted (6)
[runnervmeorf1:04510] Signal code:  (-6)
[runnervmeorf1:04510] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7448445330]
[runnervmeorf1:04510] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f744849eb2c]
[runnervmeorf1:04510] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f744844527e]
[runnervmeorf1:04510] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f74484288ff]
[runnervmeorf1:04510] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f74488a5ff5]
[runnervmeorf1:04510] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f74488bb0da]
[runnervmeorf1:04510] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f74488a5a55]
[runnervmeorf1:04510] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f74488a5a6f]
[runnervmeorf1:04510] [ 8] plumed_master(+0x146dd)[0x5559bf5af6dd]
[runnervmeorf1:04510] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f744842a1ca]
[runnervmeorf1:04510] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f744842a28b]
[runnervmeorf1:04510] [11] plumed_master(+0x15365)[0x5559bf5b0365]
[runnervmeorf1:04510] *** End of error message ***
</pre>
{% endraw %}
