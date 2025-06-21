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
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:15630] *** Process received signal ***
[pkrvmxyh4eaekms:15630] Signal: Aborted (6)
[pkrvmxyh4eaekms:15630] Signal code:  (-6)
[pkrvmxyh4eaekms:15630] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f93a6645330]
[pkrvmxyh4eaekms:15630] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f93a669eb2c]
[pkrvmxyh4eaekms:15630] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f93a664527e]
[pkrvmxyh4eaekms:15630] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f93a66288ff]
[pkrvmxyh4eaekms:15630] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f93a6aa5ff5]
[pkrvmxyh4eaekms:15630] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f93a6abb0da]
[pkrvmxyh4eaekms:15630] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f93a6aa5a55]
[pkrvmxyh4eaekms:15630] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f93a6aa5a6f]
[pkrvmxyh4eaekms:15630] [ 8] plumed_master(+0x146dd)[0x5624788206dd]
[pkrvmxyh4eaekms:15630] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f93a662a1ca]
[pkrvmxyh4eaekms:15630] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f93a662a28b]
[pkrvmxyh4eaekms:15630] [11] plumed_master(+0x15365)[0x562478821365]
[pkrvmxyh4eaekms:15630] *** End of error message ***
</pre>
{% endraw %}
