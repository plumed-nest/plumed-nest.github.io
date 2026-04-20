**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/tetramer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @38 : keyword ARG is compulsory for this action
[runnervmeorf1:04588] *** Process received signal ***
[runnervmeorf1:04588] Signal: Aborted (6)
[runnervmeorf1:04588] Signal code:  (-6)
[runnervmeorf1:04588] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3632045330]
[runnervmeorf1:04588] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f363209eb2c]
[runnervmeorf1:04588] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f363204527e]
[runnervmeorf1:04588] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36320288ff]
[runnervmeorf1:04588] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f36324a5ff5]
[runnervmeorf1:04588] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f36324bb0da]
[runnervmeorf1:04588] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f36324a5a55]
[runnervmeorf1:04588] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f36324a5a6f]
[runnervmeorf1:04588] [ 8] plumed_master(+0x146dd)[0x564ae58af6dd]
[runnervmeorf1:04588] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f363202a1ca]
[runnervmeorf1:04588] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f363202a28b]
[runnervmeorf1:04588] [11] plumed_master(+0x15365)[0x564ae58b0365]
[runnervmeorf1:04588] *** End of error message ***
</pre>
{% endraw %}
