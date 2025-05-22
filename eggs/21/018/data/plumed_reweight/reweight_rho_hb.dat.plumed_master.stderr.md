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
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:38000] *** Process received signal ***
[pkrvmf6wy0o8zjz:38000] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38000] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38000] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f62aac45330]
[pkrvmf6wy0o8zjz:38000] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f62aac9eb2c]
[pkrvmf6wy0o8zjz:38000] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f62aac4527e]
[pkrvmf6wy0o8zjz:38000] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62aac288ff]
[pkrvmf6wy0o8zjz:38000] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62ab0a5ff5]
[pkrvmf6wy0o8zjz:38000] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62ab0bb0da]
[pkrvmf6wy0o8zjz:38000] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62ab0a5a55]
[pkrvmf6wy0o8zjz:38000] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62ab0a5a6f]
[pkrvmf6wy0o8zjz:38000] [ 8] plumed_master(+0x146dd)[0x561beb4046dd]
[pkrvmf6wy0o8zjz:38000] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f62aac2a1ca]
[pkrvmf6wy0o8zjz:38000] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f62aac2a28b]
[pkrvmf6wy0o8zjz:38000] [11] plumed_master(+0x15365)[0x561beb405365]
[pkrvmf6wy0o8zjz:38000] *** End of error message ***
</pre>
{% endraw %}
