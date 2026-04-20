**Project ID:** [plumID:19.017]({{ '/' | absolute_url }}eggs/19/017/)  
Stderr for source:  plumed_reweight/reweight_rho_c.dat   
Download: [zipped raw stdout](reweight_rho_c.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_c.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmeorf1:11796] *** Process received signal ***
[runnervmeorf1:11796] Signal: Aborted (6)
[runnervmeorf1:11796] Signal code:  (-6)
[runnervmeorf1:11796] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5345e45330]
[runnervmeorf1:11796] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5345e9eb2c]
[runnervmeorf1:11796] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5345e4527e]
[runnervmeorf1:11796] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5345e288ff]
[runnervmeorf1:11796] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f53462a5ff5]
[runnervmeorf1:11796] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f53462bb0da]
[runnervmeorf1:11796] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f53462a5a55]
[runnervmeorf1:11796] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f53462a5a6f]
[runnervmeorf1:11796] [ 8] plumed_master(+0x146dd)[0x5635888286dd]
[runnervmeorf1:11796] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5345e2a1ca]
[runnervmeorf1:11796] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5345e2a28b]
[runnervmeorf1:11796] [11] plumed_master(+0x15365)[0x563588829365]
[runnervmeorf1:11796] *** End of error message ***
</pre>
{% endraw %}
