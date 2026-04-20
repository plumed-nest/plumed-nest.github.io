**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
Stderr for source:  plumed_reweight/reweight_rho_hb.dat   
Download: [zipped raw stdout](reweight_rho_hb.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed_master.stderr.txt.zip) 
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
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervmeorf1:08737] *** Process received signal ***
[runnervmeorf1:08737] Signal: Aborted (6)
[runnervmeorf1:08737] Signal code:  (-6)
[runnervmeorf1:08737] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbfd6645330]
[runnervmeorf1:08737] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbfd669eb2c]
[runnervmeorf1:08737] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbfd664527e]
[runnervmeorf1:08737] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbfd66288ff]
[runnervmeorf1:08737] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbfd6aa5ff5]
[runnervmeorf1:08737] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbfd6abb0da]
[runnervmeorf1:08737] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbfd6aa5a55]
[runnervmeorf1:08737] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbfd6aa5a6f]
[runnervmeorf1:08737] [ 8] plumed_master(+0x146dd)[0x55a8ce0756dd]
[runnervmeorf1:08737] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbfd662a1ca]
[runnervmeorf1:08737] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbfd662a28b]
[runnervmeorf1:08737] [11] plumed_master(+0x15365)[0x55a8ce076365]
[runnervmeorf1:08737] *** End of error message ***
</pre>
{% endraw %}
